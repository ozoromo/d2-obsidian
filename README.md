# D2 Support for Obsidian

## Installation

### Installing the Plugin on Obsidian

Settings > Community plugins > Browse > Search for D2

### Installing D2

D2 must be installed for this plugin to work, for instructions on how to install D2, click [here](https://github.com/terrastruct/d2#install)

### Configuring the Plugin

-   `Layout engine`: Layout engines we support include `dagre`, `ELK`, and `TALA` (`TALA` must be installed separately from D2. For more information on how to install TALA, click [here](https://github.com/terrastruct/tala))
-   `API token`: To use TALA, copy your Terrastruct API token here or in `~/.local/state/tstruct/auth.json` under the field `api_token`. The API Token is located in your Terrastruct console.
-   `Theme ID`: For a list of available themes, click [here](https://github.com/terrastruct/d2/tree/master/d2themes)
-   `Debounce`: How often you want the diagram to refresh in second(s)

## Using the Plugin

Create a fenced codeblock using d2 as the language and type in your D2 DSL, such as:

````
```d2
Hello -> World
```
````

## How to run this plugin locally

-   Clone this repo.
-   `npm i` or `yarn` to install dependencies
-   `npm run dev` to start compilation in watch mode.
-   Copy over `main.js`, `styles.css`, `manifest.json` to your vault `[VaultFolder]/.obsidian/plugins/d2/`.

# VSCode Extension for FDS Input Files
## Features

This extension for Visual Studio Code is used for syntax highlighting of FDS input files. In addition, the extension provides snippets that enable autocompletion of certain commands and namelist groups.

## How to install this extension

* Download the extension from [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=openbcl.fds).

## Extension Settings

This extension contributes the following settings through the `contributes.configurationDefaults` extension point:

```json
"[fds]": {
    "editor.tabSize": 6,
    "editor.snippetSuggestions": "top",
    "editor.suggest.showSnippets": true
}
```

## Known Issues

- Currently snippets for the following namelist groups are only provided without any parameters: COMB, GEOM, HVAC, INIT, MOVE, MULT, PART, PRES, PROP, RADI, SPEC, WIND, ZONE. These snippets are marked in their description by the addition "missing parameters".

- Some snippets for specific namelist groups only provide the most common parameters. You can distinguish the snippets of namelist groups with partial parameters from those with complete parameters by looking for the additional information "partial parameters" and "complete parameters" in the description.
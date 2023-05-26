# VSCode Extension for FDS Input Files
## Features

This extension for Visual Studio Code is used for syntax highlighting of FDS input files. In addition, the extension provides snippets that enable autocompletion of certain commands and namelist groups.

## How to install this extension

* Download the extension from [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=FDS).

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

Currently only snippets for the namelist groups "HEAD" and "MESH" are supported. For the remaining groups, no autocompletion for parameters has been implemented yet.
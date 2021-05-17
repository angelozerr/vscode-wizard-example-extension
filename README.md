# vscode-wizard

[![Code Style: Google](https://img.shields.io/badge/code%20style-google-blueviolet.svg)](https://github.com/google/gts)

vscode-wizard-example-extension is a vscode-extension using the npm module [vscode-wizard](https://github.com/redhat-developer/vscode-wizard) to display wizards in webviews inside VS Code. 

# vscode-wizard

[vscode-wizard](https://github.com/redhat-developer/vscode-wizard) is a fork and large expansion in the API of [vscode-page](https://github.com/DTeam-Top/vscode-page), aiming to create wizards out of a javascript object definition that includes pages, fields, validators, and option providers for combos. See [vscode-wizard](https://github.com/redhat-developer/vscode-wizard) for more information. 

## Features

This repo demonstrates the various widgets and validation methods available in [vscode-wizard](https://github.com/redhat-developer/vscode-wizard). 

## Installing

Once inside the project folder, execute the following:

```shell
npm install
npm run build
vsce package
```

## Usage

To demonstrate this example, use the command prompt in vscode (ctrl+shift+p) to execute the command `ext.home`. This should bring up a webview with the suggested UI. 


## Release Notes

### 0.0.1

First release.

## License

`vscode-wizard-example-extension` is released under the Apache License 2.0 license.

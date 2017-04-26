# VSCode Extension - Kamailio Syntax Highlighting

This Visual Studio Code (VSCode) extension provides syntax highlighting for editing Kamailio SIP Server configuration files.

More details about Kamailio SIP Server project can be found at:

  * https://www.kamailio.org

The code for this extension is hosted at:

  * https://github.com/miconda/vscode-kamailio-syntax

## Features

Syntax highlighting for:

  * line comments
  * block comments
  * preprocessor directive
  * routing block names
  * variables
  * string and integer values
  * reserved keywords

A screenshot while editing the kamailio.cfg file with this extension enabled:

![Usage Example](https://raw.githubusercontent.com/miconda/vscode-kamailio-syntax/master/images/vscode-kamailio-syntax.png)

## Installation

The extension is published on VSCode Marketplace at:

  * https://marketplace.visualstudio.com/items?itemName=miconda.kamailio-syntax

To install it from the marketplace, launch VS Code Quick Open (`Cmd+P` or `⌘+P`), paste the following command, and press enter.

```
ext install kamailio-syntax
```

To install from Git repository, clone it to your account VSCode folder (on MacOS or Linux, that is `~/.vscode/extensions`):

```
cd ~/.vscode/extensions
git clone https://github.com/miconda/vscode-kamailio-syntax
```

The extension needs to be enabled from VSCode preferences.

## Known Issues

Tested only on MacOS.

## Release Notes

### 1.0.1 (2017-04-26)

  * matching rules for a few more keywords
  * highlight single quoted strings

### 1.0.0 (2017-04-24)

  * initial release

**Enjoy!**
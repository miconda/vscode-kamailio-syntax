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
  * variables, indexes and transformations
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

Tested on MacOS, Linux, Windows (10)


## Release Notes

## 1.0.8 (2020-12-01)

  * added name to control keywords list
  * added defenv to defines list
  * added all file type line
  * catch empty comment line started with #
  * match variables with index and transformations
  * the index and transformations are highlighted separately
  * split conditionals from keywords
  * highlight control functions in own group

For release notes of older versions, see [CHANGELOG.md](https://github.com/miconda/vscode-kamailio-syntax/blob/master/CHANGELOG.md) file.

**Enjoy!**

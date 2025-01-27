# Everscale Solidity support for Visual Studio Code (DEPRECATED)

THIS EXTENSION WILL BE ARCHIVED DUE TO REBRANDING. PLEASE USE [everscale.solidity-support](https://marketplace.visualstudio.com/items?itemName=everscale.solidity-support)


[Everscale (TON) Solidity](https://github.com/tonlabs/TON-Solidity-Compiler/blob/master/API.md) is the language used in Everscale blockchain to create smart contracts. This extension provides:

* Syntax highlighting
* Snippets with details
* Checking for errors, warnings and highlighting it
* Display an information popup on hover
* Suggesting function params when typing
* [DeBots interfaces](https://github.com/tonlabs/DeBot-IS-consortium) highlighting, autocompletion, support for imports

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install zfreeton.ton-solidity`

### CLI

With [shell commands](https://code.visualstudio.com/docs/editor/command-line) installed, you can use the following command to install the extension:

`$ code --install-extension zfreeton.ton-solidity`

## Features

### Highlighting

For example, light and dark themes: "Solarized Light" and "Material Theme":
![solarized-light](https://user-images.githubusercontent.com/26024499/138431546-a7ddef6a-8a6b-4f85-b166-bc2a84517a0e.png) ![material-theme](https://user-images.githubusercontent.com/26024499/138431539-3f96068f-ea6c-47be-ab80-b7b49e7b6bf1.png)

### Ton-solidity autocomplete with detailed information

Use ```Ctrl+Space```

![autocomplete-with-detailed-information](https://user-images.githubusercontent.com/26024499/138431513-3a1880b8-5eb0-4e27-a854-f258c4bd5c90.gif)

### Contract's functions autocompletion

![contract-functions-autocomplete](https://user-images.githubusercontent.com/26024499/138431524-463b2c0d-fb50-462a-ad0f-b3a59c021245.gif)

### Code diagnostic on the fly

![code-diagnostic](https://user-images.githubusercontent.com/26024499/138431522-86109d28-eec1-4a31-b522-c322c1ab60f5.gif)

### On hover information

![hover-information](https://user-images.githubusercontent.com/26024499/138431525-98347356-0530-436e-9daa-f302ce7c4445.gif)

### Params helper

![params-helper](https://user-images.githubusercontent.com/26024499/138431543-9a5e5fc6-6e2d-41f4-b580-8c69283418a2.gif)

This extension only working with TON Solidity language. If You are using Ethereum Solidity, use other extensions for this.
You have quick switch between two solidity languages:

![language-switcher](https://user-images.githubusercontent.com/26024499/138431534-41d648c2-6770-44eb-a523-2404cf481015.gif)

## How to contribute

If You found a typo or want to improve something, a pull request is welcome.
Some files meaning and locations:

```./src/snippets/completion.json``` — almost all completions snippets

```./src/snippets/hover.json``` — all hover popups

```./src/syntaxes/ton-solidity.json``` — syntax highlighting rules

## Contacts

Telegram: ```@tg2020ukraine```

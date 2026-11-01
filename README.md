# BOURMADA Language Support

A lightweight Visual Studio Code extension that adds syntax highlighting and editor language settings for `.bmd` files written in the BOURMADA language.

## Features

- Syntax highlighting for comments, strings, numbers, booleans, operators, keywords, and function names
- Basic bracket and quote auto-closing support
- Language configuration for `.bmd` files

## Usage

Open a file with the `.bmd` extension in VS Code, and the BOURMADA grammar will be applied automatically.

## Publishing

This extension is ready to be packaged with the VS Code Extension CLI:

```bash
npx @vscode/vsce package
```

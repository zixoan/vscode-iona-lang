# iona language support for vs code

[Iona language](https://github.com/zixoan/iona) support for Visual Studio Code which adds syntax highlighting and code snippets.

## Features

- Syntax highlighting
- Code snippets
    - Main function (main)
    - WriteLine() (print/write)
    - WriteLine("") (prints/writes)
    - ReadLine() (read)
    - var input = ReadLine() (readv)
    - for x in array (for)

## Requirements

To package the extension you need to have [Node.js](https://nodejs.org/) installed.
Then run the following to install the VS Code Extension Manager:
```console
npm install -g vsce
```

And to finally package it:
```console
vsce package
```

This will produce a iona-lang-X.X.X.vsix file, which can be installed in Visual Studio Code.

## Issues

Check the [issues](https://github.com/zixoan/vscode-iona-lang/issues) tab to see the current issues.

## Release Notes

### 0.0.1

Initial release of iona-lang

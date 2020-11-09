# vscode-css-ls-bin

[![npm](https://img.shields.io/npm/v/vscode-css-ls-bin.svg)](https://www.npmjs.com/package/vscode-css-ls-bin)

CSS Language Server binary built directly from [VSCode](https://github.com/microsoft/vscode).

Inspired by [vscode-langservers/vscode-css-languageserver-bin](https://github.com/vscode-langservers/vscode-css-languageserver-bin/)

## Prerequisites

To install this Language Server you need [npm](https://www.npmjs.com/get-npm) on your machine

## Installing

```bash
npm install --global vscode-css-ls-bin
```

## Launching the Server

The common way to launch it is by using stdio transport:

```bash
css-ls --stdio
```

The server can also be launched with one of the following transports:

```bash
css-ls --socket={number}
css-ls --node-ipc
```

## Versioning

We use [SemVer](http://semver.org/) for versioning.

`MINOR` is changed when the submodule is updated and `PATCH` when only the build method is updated.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
This is a derived work please see [VSCode's LICENSE.txt](https://github.com/Microsoft/vscode/blob/master/LICENSE.txt) for the original copyright and license.

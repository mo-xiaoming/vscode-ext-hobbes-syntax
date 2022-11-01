# hobbes syntax highlighting

Syntax highlighting support for [hobbes](https://github.com/morganstanley/hobbes)

[![GitHub license][license-img]][license-url]

## Features

![feature image](https://raw.githubusercontent.com/mo-xiaoming/vscode-ext-hobbes-syntax/master/images/feature.png)

## Known Issues

The extension only use simple regex, doesn't try to do anything fancy, so it won't work in all cases.

For example, char and regex in hobbes both use `'` as the begin and end delimiters. If one character between `'`s, then it is a char, otherwise it is a regex. This extension doesn't extinguish these two types, they both get recognized as regex.

## Release Notes

### 0.1.0

* Provides basic syntax highlighting

---

## Other links

* [hobbes language](https://github.com/morganstanley/hobbes)
* [repository](https://github.com/mo-xiaoming/vscode-ext-hobbes-syntax)

**Enjoy!**

[license-img]: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
[license-url]: https://raw.githubusercontent.com/mo-xiaoming/vscode-ext-hobbes-syntax/master/LICENSE
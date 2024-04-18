# Lorem Ipsum Generator

Provides a slash command for STscript that generates a Lorem Ipsum text and outputs it to the pipe.

## Installation

Install using a third-party extensions installer using the following URL:

```
https://github.com/SillyTavern/Extension-LoremIpsum
```

## Usage

```
/lorem units=p count=1 separator=" "
```

## Arguments

* units: enum { p(aragraphs) / w(ords) / s(entences) }. Default: paragraphs.
* count: integer. Default: 1.
* separator: string. Default: double newline.

## Credits

Licensed under AGPLv3.

Uses code from [fffilo/lorem-ipsum-js](https://raw.githubusercontent.com/fffilo/lorem-ipsum-js/master/src/lorem-ipsum.js)

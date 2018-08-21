# first_npm_module

# @swatcat94/tiny

[![npm (scoped)](https://img.shields.io/badge/npm-v2.0.0-lightgreen.svg
)](https://www.npmjs.com/package/@swatcat94/tiny)
<!-- [![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@bamblehorse/tiny) -->

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```





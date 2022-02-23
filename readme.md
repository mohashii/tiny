# @mohashii/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@mohashii/tiny.svg)](https://www.npmjs.com/package/@mohashii/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mohashii/tiny.svg)](https://www.npmjs.com/package/@mohashii/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @mohashii/tiny
```

## Usage

```js
const tiny = require("@mohashii/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
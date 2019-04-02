# @sarithats/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@sarithats/tiny.svg)](https://www.npmjs.com/package/@sarithats/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@sarithats/tiny.svg)](https://www.npmjs.com/package/@sarithats/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @sarithats/tiny
```

## Usage

```js
const tiny = require("@sarithats/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
# @balugo/css-template

[![npm (scoped)](https://img.shields.io/npm/v/@windix/npm-tiny.svg)](https://www.npmjs.com/package/@windix/npm-tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@windix/npm-tiny.svg)](https://www.npmjs.com/package/@windix/npm-tiny)

Removes all spaces from a string.

## Install

```bash
$ npm install @windix/npm-tiny
```

## Usage

```js
const tiny = require("@windix/npm-tiny");

tiny('So much space!');
//=> "Somuchspace!"

tiny(123);
//=> Uncaught TypeError: tiny expects a string!
```

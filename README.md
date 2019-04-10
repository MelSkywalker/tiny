# @mel.skywalker/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@mel.skywalker/tiny.svg)](https://github.com/MelSkywalker/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/tiny.svg)](https://github.com/MelSkywalker/tiny)

Removes all spaces from a string

##Install
```
$npm install @mel.skywalker/tiny
```

##Usage
```js
const tiny = require("@mel.skywalker/tiny");
tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
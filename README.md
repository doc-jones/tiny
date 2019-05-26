![npm (scoped)](https://img.shields.io/npm/v/@doc.jones/tiny.svg)
![npm bundle size](https://img.shields.io/bundlephobia/min/tiny.svg?color=orange)
# tiny
The world's smallest and my 1st npm package. 
Removes all spaces from a string.

# Install
```$ npm install @doc.jones/tiny```


# Usage
```const tiny = require("@doc.jones/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1```

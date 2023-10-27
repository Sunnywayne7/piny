## @sunnywayne/piny
<p align="center">
  <img src="https://img.shields.io/npm/v/%40sunnywayne/piny" alt="npm version(scoped)">
</p>



<p align="center">
  <img src="https://img.shields.io/bundlephobia/min/%40sunnywayne/piny" alt="npm bundle size (scoped)">
</p>

Removes all spaces from a string

## Install

```
$ npm install @sunnywayne/piny
```

## Usage

```
const piny = require("@sunnywayne/piny");

piny("I dont like space at all");
//=> "Idontlikespaceatall"

piny(1337);
//=>Uncaught TypeError: piny wants a string!
// at tiny (<anonymous>:2:41)
// at <anonymous>:1:1

```
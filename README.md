# short-hash-ts

-> Get a quick hash that uses the well-liked Bernstein "times 33" hash method and delivers a hex string.

## Installation

Install `short-hash-ts` using [npm](https://www.npmjs.com/):

```bash
npm i short-hash-ts
```


## Usage

#### Creating a hash string 

```javascript
import shorthash from 'short-hash-ts';
OR
var shorthash = require('short-hash-ts');


console.log(shorthash.unique('name'));
// you will get: eQEF

console.log(shorthash.unique('https://younisrahman.com/'));
// you will get: Z10i5MF

console.log(shorthash.unique('The quick brown fox jumps over the lazy dog'));
// you will get: ZI0UJg

console.log(shorthash.unique('আমি বাংলা বলতে পারি'));
// you will get: Z2tKMTX

```
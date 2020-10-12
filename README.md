# is-process [![Build Status](https://travis-ci.org/MeLike2D/is-process.svg?branch=master)](https://travis-ci.org/MeLike2D/is-process)

> Check whether a value is the process.

## Install

```shell script
$ npm install is-process
```

## Usage

```js
const isProcess = require("is-process");
isProcess(process);
// => true

isProcess({});
// => false

isProcess(42069);
// => false
```

---

<p align="center">NPM <3</p>

safename
========

Get safe file name from a given string.

[![Build Status](https://travis-ci.org/jacoborus/safename.svg?branch=master)](https://travis-ci.org/jacoborus/safename)


## Example

```js
// require only in node/browserify
var safename = require( 'safename' );

safename('my file name.txt');
// => my_file_name.txt

safename('my file name.txt', '-');
// => my-file-name.txt

safename.low('my file name.txt');
// => my_file_name.txt

safename.middle('my file name.txt');
// => my-file-name.txt

safename.dot('my file name.txt');
// => my.file.name.txt
```



## Installation

Install with npm
```
$ npm install safename
```

Install with Bower
```
$ bower install safename
```



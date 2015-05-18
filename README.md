# is-sorted

[![TRAVIS](https://secure.travis-ci.org/dcousens/is-sorted.png)](http://travis-ci.org/dcousens/is-sorted)
[![NPM](http://img.shields.io/npm/v/is-sorted.svg)](https://www.npmjs.org/package/is-sorted)

A small module to check if an Array is sorted.


## Example

``` javascript
var sorted = require('is-sorted')

console.log(sorted([1, 2, 3]))
// => true

console.log(sorted([3, 1, 2]))
// => false

// supports custom comparators
console.log(sorted([3, 2, 1], function (a, b) { return b - a })
// => true
```


## License

This library is free and open-source software released under the MIT license.

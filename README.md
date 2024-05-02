# @tea062024/facilis-fugit-quam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@tea062024/facilis-fugit-quam');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@tea062024/facilis-fugit-quam
[npm-version-svg]: https://versionbadg.es/inspect-js/@tea062024/facilis-fugit-quam.svg
[deps-svg]: https://david-dm.org/inspect-js/@tea062024/facilis-fugit-quam.svg
[deps-url]: https://david-dm.org/inspect-js/@tea062024/facilis-fugit-quam
[dev-deps-svg]: https://david-dm.org/inspect-js/@tea062024/facilis-fugit-quam/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@tea062024/facilis-fugit-quam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@tea062024/facilis-fugit-quam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@tea062024/facilis-fugit-quam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@tea062024/facilis-fugit-quam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@tea062024/facilis-fugit-quam
[codecov-image]: https://codecov.io/gh/inspect-js/@tea062024/facilis-fugit-quam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@tea062024/facilis-fugit-quam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@tea062024/facilis-fugit-quam
[actions-url]: https://github.com/tea062024/facilis-fugit-quam/actions

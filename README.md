# @emiplegiaqmnpm/esse-quos-sunt <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@emiplegiaqmnpm/esse-quos-sunt');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/esse-quos-sunt
[npm-version-svg]: https://versionbadg.es/inspect-js/@emiplegiaqmnpm/esse-quos-sunt.svg
[deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/esse-quos-sunt.svg
[deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/esse-quos-sunt
[dev-deps-svg]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/esse-quos-sunt/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@emiplegiaqmnpm/esse-quos-sunt#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/esse-quos-sunt.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/esse-quos-sunt.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/esse-quos-sunt.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/esse-quos-sunt
[codecov-image]: https://codecov.io/gh/inspect-js/@emiplegiaqmnpm/esse-quos-sunt/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@emiplegiaqmnpm/esse-quos-sunt/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@emiplegiaqmnpm/esse-quos-sunt
[actions-url]: https://github.com/emiplegiaqmnpm/esse-quos-sunt/actions

# @zitterorg/natus-eos-vel <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const humanFileSize = require('@zitterorg/natus-eos-vel');

console.log(humanFileSize(67229)); //67.2 KB
console.log(humanFileSize(67229, true, 2)); //67.23 KB
console.log(humanFileSize(67229, false)); //65.7 KiB
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/natus-eos-vel
[npm-version-svg]: https://versionbadg.es/zitterorg/natus-eos-vel.svg
[npm-badge-png]: https://nodei.co/npm/@zitterorg/natus-eos-vel.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/natus-eos-vel.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/natus-eos-vel.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/natus-eos-vel
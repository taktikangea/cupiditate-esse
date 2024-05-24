# @taktikangea/cupiditate-esse <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`Iterator.prototype`, or a shared object to use.

## Usage

```javascript
var iterProto = require('@taktikangea/cupiditate-esse');
var assert = require('assert');

assert.equal(Object.getPrototypeOf(Object.getPrototypeOf([].keys())), iterProto);
```

[package-url]: https://npmjs.org/package/@taktikangea/cupiditate-esse
[npm-version-svg]: https://versionbadg.es/taktikangea/cupiditate-esse.svg
[deps-svg]: https://david-dm.org/taktikangea/cupiditate-esse.svg
[deps-url]: https://david-dm.org/taktikangea/cupiditate-esse
[dev-deps-svg]: https://david-dm.org/taktikangea/cupiditate-esse/dev-status.svg
[dev-deps-url]: https://david-dm.org/taktikangea/cupiditate-esse#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@taktikangea/cupiditate-esse.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikangea/cupiditate-esse.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikangea/cupiditate-esse.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikangea/cupiditate-esse
[codecov-image]: https://codecov.io/gh/taktikangea/cupiditate-esse/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/taktikangea/cupiditate-esse/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/taktikangea/cupiditate-esse
[actions-url]: https://github.com/taktikangea/cupiditate-esse/actions

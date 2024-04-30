# @devtea2026/quae-tempora-error-modi <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple cache for a few of the JS Error constructors.

## Example

```js
const assert = require('assert');

const Base = require('@devtea2026/quae-tempora-error-modi');
const Eval = require('@devtea2026/quae-tempora-error-modi/eval');
const Range = require('@devtea2026/quae-tempora-error-modi/range');
const Ref = require('@devtea2026/quae-tempora-error-modi/ref');
const Syntax = require('@devtea2026/quae-tempora-error-modi/syntax');
const Type = require('@devtea2026/quae-tempora-error-modi/type');
const URI = require('@devtea2026/quae-tempora-error-modi/uri');

assert.equal(Base, Error);
assert.equal(Eval, EvalError);
assert.equal(Range, RangeError);
assert.equal(Ref, ReferenceError);
assert.equal(Syntax, SyntaxError);
assert.equal(Type, TypeError);
assert.equal(URI, URIError);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@devtea2026/quae-tempora-error-modi
[npm-version-svg]: https://versionbadg.es/ljharb/@devtea2026/quae-tempora-error-modi.svg
[deps-svg]: https://david-dm.org/ljharb/@devtea2026/quae-tempora-error-modi.svg
[deps-url]: https://david-dm.org/ljharb/@devtea2026/quae-tempora-error-modi
[dev-deps-svg]: https://david-dm.org/ljharb/@devtea2026/quae-tempora-error-modi/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@devtea2026/quae-tempora-error-modi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/quae-tempora-error-modi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/quae-tempora-error-modi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/quae-tempora-error-modi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/quae-tempora-error-modi
[codecov-image]: https://codecov.io/gh/ljharb/@devtea2026/quae-tempora-error-modi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@devtea2026/quae-tempora-error-modi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@devtea2026/quae-tempora-error-modi
[actions-url]: https://github.com/devtea2026/quae-tempora-error-modi/actions

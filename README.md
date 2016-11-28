# unescape [![NPM version](https://img.shields.io/npm/v/unescape.svg?style=flat)](https://www.npmjs.com/package/unescape) [![NPM monthly downloads](https://img.shields.io/npm/dm/unescape.svg?style=flat)](https://npmjs.org/package/unescape)  [![NPM total downloads](https://img.shields.io/npm/dt/unescape.svg?style=flat)](https://npmjs.org/package/unescape) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/unescape.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/unescape)

> Convert HTML entities to HTML characters, e.g. `&gt;` converts to `>`.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save unescape
```

## Usage

```js
var unescape = require('unescape');
console.log(unescape('&lt;div&gt;abc&lt;/div&gt;'));
//=> '<div>abc</div>'
```

* `&#39;` converts to `'`
* `&amp;` converts to `&`
* `&gt;` converts to `>`
* `&lt;` converts to `<`
* `&quot;` converts to `"`

Get the characters/entities:

```js
console.log(unescape.chars);
```

returns

```js
{
  '&#39;': '\'',
  '&amp;': '&',
  '&gt;': '>',
  '&lt;': '<',
  '&quot;': '"'
}
```

## About

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Building docs

_(This document was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme) (a [verb](https://github.com/verbose/verb) generator), please don't edit the readme directly. Any changes to the readme must be made in [.verb.md](.verb.md).)_

To generate the readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install -g verb verb-generate-readme && verb
```

### Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

### License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/unescape/blob/master/LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.2.0, on November 27, 2016._
time-cache
==========

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io)
[![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)
[![Build Status](https://travis-ci.org/diasdavid/time-cache.svg?style=flat-square)](https://travis-ci.org/diasdavid/time-cache)
[![Coverage Status](https://coveralls.io/repos/github/diasdavid/time-cache/badge.svg?branch=master)](https://coveralls.io/github/diasdavid/time-cache?branch=master)
[![Dependency Status](https://david-dm.org/diasdavid/time-cache.svg?style=flat-square)](https://david-dm.org/diasdavid/time-cache)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard)

> A key-value cache that puts a expiry date on its entries.

## Table of Contents

- [Install](#install)
  - [npm](#npm)
- [Usage](#usage)
  - [Example](#example)
- [API](#api)
- [Contribute](#contribute)
- [License](#license)

## Install

### npm

```sh
> npm install time-cache
```

## Usage

### Example

```js
// TODO (see tests meanwhile)
```

## API

### Create a time-cache `const tc = new TimeCache(options)`

 - `options` (`Object`) - options object (optional)
 - `options.validity` (`Number`) - validity in seconds to keep cached items for, default: 30

### Add a value `tc.put(key, value, validity)`

- `key` (`String`) - key to store the value under
- `value` (`?`) - value to store
- `validity` - validity in seconds to keep this item for, default: 30

### Has a value `tc.has(key)`

- `key` (`String`) - key to query if the cache has a value for

### Get a value `tc.get(key)`

- `key` (`String`) - key to get value for

## Contribute

Contributions are welcome!

## License

MIT

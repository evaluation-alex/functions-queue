# functions-queue

[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![Code Climate][climate-image]][climate-url]
[![License][license-image]][license-url]
[![Code Style][code-style-image]][code-style-url]

## Getting Started

functions-queue is universal, so it can be used client-side or server-side.

1. Install through: `npm install --save functions-queue`

2. Include and use `functions-queue`:

    ```javascript
  import Queue from 'functions-queue';
  const service = new Queue();
  service
    .start()
    .then(() => {
      service.progress(10)
      service.resolve()
    })
    ```
## Testing/Coverage

`npm run test` - Run unit tests
`npm run test:cov` - Run unit tests and report coverage

## [Documentation](https://prescottprue.github.com/functions-queue)

[npm-image]: https://img.shields.io/npm/v/functions-queue.svg?style=flat-square
[npm-url]: https://npmjs.org/package/functions-queue
[travis-image]: https://img.shields.io/travis/prescottprue/functions-queue/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/prescottprue/functions-queue
[daviddm-image]: https://img.shields.io/david/prescottprue/functions-queue.svg?style=flat-square
[daviddm-url]: https://david-dm.org/prescottprue/functions-queue
[climate-image]: https://img.shields.io/codeclimate/github/prescottprue/functions-queue.svg?style=flat-square
[climate-url]: https://codeclimate.com/github/prescottprue/functions-queue
[coverage-image]: https://img.shields.io/codeclimate/coverage/github/prescottprue/functions-queue.svg?style=flat-square
[coverage-url]: https://codeclimate.com/github/prescottprue/functions-queue
[license-image]: https://img.shields.io/npm/l/functions-queue.svg?style=flat-square
[license-url]: https://github.com/prescottprue/functions-queue/blob/master/LICENSE
[code-style-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[code-style-url]: http://standardjs.com/

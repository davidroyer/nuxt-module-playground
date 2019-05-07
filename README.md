# nuxt-module-playground

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Circle CI][circle-ci-src]][circle-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![Dependencies][david-dm-src]][david-dm-href]
[![Standard JS][standard-js-src]][standard-js-href]

> Testing and working on nuxt module concepts

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add the `nuxt-module-playground` dependency with `yarn` or `npm` to your project
2. Add `nuxt-module-playground` to the `modules` section of `nuxt.config.js`
3. Configure it:

```js
{
  modules: [
    // Simple usage
    'nuxt-module-playground',

    // With options
    ['nuxt-module-playground', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) David Royer <droyer01@gmail.com>

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/dt/@droyer/nuxt-module-playground.svg?style=flat-square
[npm-version-href]: https://npmjs.com/package/@droyer/nuxt-module-playground

[npm-downloads-src]: https://img.shields.io/npm/v/@droyer/nuxt-module-playground/latest.svg?style=flat-square
[npm-downloads-href]: https://npmjs.com/package/@droyer/nuxt-module-playground

[circle-ci-src]: https://img.shields.io/circleci/project/github/davidroyer/nuxt-module-playground.svg?style=flat-square
[circle-ci-href]: https://circleci.com/gh/davidroyer/nuxt-module-playground

[codecov-src]: https://img.shields.io/codecov/c/github/davidroyer/nuxt-module-playground.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/davidroyer/nuxt-module-playground

[david-dm-src]: https://david-dm.org/davidroyer/@droyer/nuxt-module-playground/status.svg?style=flat-square
[david-dm-href]: https://david-dm.org/davidroyer/@droyer/nuxt-module-playground

[standard-js-src]: https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square
[standard-js-href]: https://standardjs.com

# nuxt-helmet

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Circle CI][circle-ci-src]][circle-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![Dependencies][david-dm-src]][david-dm-href]
[![Standard JS][standard-js-src]][standard-js-href]

> Helmet for nuxt

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add `nuxt-helmet` dependency with `yarn` or `npm` into your project
2. Add `nuxt-helmet` to `modules` section of `nuxt.config.js`
3. Configure it:

```js
{
  modules: [
    // Simple usage
    'nuxt-helmet',

    // With options
    ['nuxt-helmet', { /* module options */ }],
 ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Victor Perez <vpjs@victor-perez.nl>

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/dt/nuxt-helmet.svg?style=flat-square
[npm-version-href]: https://npmjs.com/package/nuxt-helmet

[npm-downloads-src]: https://img.shields.io/npm/v/nuxt-helmet/latest.svg?style=flat-square
[npm-downloads-href]: https://npmjs.com/package/nuxt-helmet

[circle-ci-src]: https://img.shields.io/circleci/project/github/git@github.com:victor-perez/nuxt-helmet.git.svg?style=flat-square
[circle-ci-href]: https://circleci.com/gh/git@github.com:victor-perez/nuxt-helmet.git

[codecov-src]: https://img.shields.io/codecov/c/github/git@github.com:victor-perez/nuxt-helmet.git.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/git@github.com:victor-perez/nuxt-helmet.git

[david-dm-src]: https://david-dm.org/git@github.com:victor-perez/nuxt-helmet.git/status.svg?style=flat-square
[david-dm-href]: https://david-dm.org/git@github.com:victor-perez/nuxt-helmet.git

[standard-js-src]: https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square
[standard-js-href]: https://standardjs.com

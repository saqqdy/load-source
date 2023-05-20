<div style="text-align: center;" align="center">

# load-source

A simple function for load js/image/css/style

[![NPM version][npm-image]][npm-url]
[![Codacy Badge][codacy-image]][codacy-url]
[![Test coverage][codecov-image]][codecov-url]
[![npm download][download-image]][download-url]
[![gzip][gzip-image]][gzip-url]
[![License][license-image]][license-url]

[![Sonar][sonar-image]][sonar-url]

</div>

<div style="text-align: center; margin-bottom: 20px;" align="center">

</div>

## Installing

```bash
# use pnpm
$ pnpm install load-source

# use npm
$ npm install load-source --save

# use yarn
$ yarn add load-source
```

## Usage

### General use

```js
import loadSource from 'load-source'

loadSource('js/image/css/style', options)
```

2. by require

```js
const loadSource = require('load-source')

loadSource('js/image/css/style', options)
```

### Use CDN resource

```html
<!-- head -->
<script src="https://unpkg.com/load-source@1.0.0/dist/load-source.global.prod.js"></script>
```

## Support & Issues

Please open an issue [here](https://github.com/saqqdy/load-source/issues).

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/load-source.svg?style=flat-square
[npm-url]: https://npmjs.org/package/load-source
[codacy-image]: https://app.codacy.com/project/badge/Grade/f70d4880e4ad4f40aa970eb9ee9d0696
[codacy-url]: https://www.codacy.com/gh/saqqdy/load-source/dashboard?utm_source=github.com&utm_medium=referral&utm_content=saqqdy/load-source&utm_campaign=Badge_Grade
[codecov-image]: https://img.shields.io/codecov/c/github/saqqdy/load-source.svg?style=flat-square
[codecov-url]: https://codecov.io/github/saqqdy/load-source?branch=master
[download-image]: https://img.shields.io/npm/dm/load-source.svg?style=flat-square
[download-url]: https://npmjs.org/package/load-source
[gzip-image]: http://img.badgesize.io/https://unpkg.com/load-source/dist/load-source.global.prod.js?compression=gzip&label=gzip%20size:%20JS
[gzip-url]: http://img.badgesize.io/https://unpkg.com/load-source/dist/load-source.global.prod.js?compression=gzip&label=gzip%20size:%20JS
[license-image]: https://img.shields.io/badge/License-MIT-blue.svg
[license-url]: LICENSE
[sonar-image]: https://sonarcloud.io/api/project_badges/quality_gate?project=saqqdy_load-source
[sonar-url]: https://sonarcloud.io/dashboard?id=saqqdy_load-source

# accessible-nav

![Node](https://img.shields.io/node/v/accessible-nav.svg?style=flat-square)
[![NPM](https://img.shields.io/npm/v/accessible-nav.svg?style=flat-square)](https://www.npmjs.com/package/accessible-nav)
[![Travis](https://img.shields.io/travis/elivz/accessible-nav/master.svg?style=flat-square)](https://travis-ci.org/elivz/accessible-nav)
[![David](https://img.shields.io/david/elivz/accessible-nav.svg?style=flat-square)](https://david-dm.org/elivz/accessible-nav)
[![Coverage Status](https://img.shields.io/coveralls/elivz/accessible-nav.svg?style=flat-square)](https://coveralls.io/github/elivz/accessible-nav)
[![NPM](https://img.shields.io/npm/dt/accessible-nav.svg?style=flat-square)](https://www.npmjs.com/package/accessible-nav)

> An script to provide responsive and keyboard-friendly drop-down navigation functionality.

### Usage

```js
import accessibleNav from 'accessible-nav';

```

### Installation

Install via [yarn](https://github.com/yarnpkg/yarn)

	yarn add accessible-nav (--dev)

or npm

	npm install accessible-nav (--save-dev)


### configuration

You can pass in extra options as a configuration object (➕ required, ➖ optional, ✏️ default).

```js
import accessibleNav from 'accessible-nav';

```

➖ **property** ( type ) ` ✏️ default `
<br/> 📝 description
<br/> ❗️ warning
<br/> ℹ️ info
<br/> 💡 example

### methods

#### #name

```js
accessibleNav

```

### Examples

See [`example`](example/script.js) folder or the [runkit](https://runkit.com/elivz/accessible-nav) example.

### Builds

If you don't use a package manager, you can [access `accessible-nav` via unpkg (CDN)](https://unpkg.com/accessible-nav/), download the source, or point your package manager to the url.

`accessible-nav` is compiled as a collection of [CommonJS](http://webpack.github.io/docs/commonjs.html) modules & [ES2015 modules](http://www.2ality.com/2014/0
  -9/es6-modules-final.html) for bundlers that support the `jsnext:main` or `module` field in package.json (Rollup, Webpack 2)

The `accessible-nav` package includes precompiled production and development [UMD](https://github.com/umdjs/umd) builds in the [`dist/umd` folder](https://unpkg.com/accessible-nav/dist/umd/). They can be used directly without a bundler and are thus compatible with many popular JavaScript module loaders and environments. You can drop a UMD build as a [`<script>` tag](https://unpkg.com/accessible-nav) on your page. The UMD builds make `accessible-nav` available as a `window.accessibleNav` global variable.

### License

The code is available under the [MIT](LICENSE) license.

### Contributing

We are open to contributions, see [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

### Misc

This module was created using [generator-module-boilerplate](https://github.com/duivvv/generator-module-boilerplate).

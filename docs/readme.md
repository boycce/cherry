![](./assets/imgs/cherry.jpg)

[![NPM](https://img.shields.io/npm/v/cherry.svg)](https://www.npmjs.com/package/cherry) [![Build Status](https://travis-ci.com/boycce/cherry.svg?branch=master)](https://travis-ci.com/boycce/cherry)

## Install

This repository is distributed with NPM. After installing NPM, you can install Cherry CSS via:

```sh
npm install --save cherry
```

## Usage

After installation, you can then import the SCSS into your project sourcing from your `node_modules` directory:

```scss
@import "../node_modules/cherry/cherry.scss";

// Or to modify the SASS variables, import like so

@import "../node_modules/cherry/scss/variables.scss";
// Your variable definitions here
// e.g. $primary: blue;
@import "../node_modules/cherry/cherry.scss";
```

## Browser Support

Cherry uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Cherry is compatible with **recent** versions of:

* Chrome
* Edge
* Explorer 10+ (partially supported)
* Firefox
* Opera
* Safari

## Special Thanks

[Willy Blandin](https://github.com/blandinw)
[The Bulma Project](https://github.com/jgthms/bulma)

## Copyright and license

Copyright 2019 Ricky Boyce. Code released under [the MIT license](https://github.com/boycce/cherry/blob/master/LICENSE).

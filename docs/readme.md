![](./assets/imgs/cherry.jpg)

[![NPM](https://img.shields.io/npm/v/css-cherry.svg)](https://www.npmjs.com/package/css-cherry) [![Build Status](https://travis-ci.org/boycce/cherry.svg?branch=master)](https://travis-ci.org/boycce/cherry)

## Install

This repository is distributed with NPM. After installing NPM, you can install Cherry CSS via:

```sh
npm install --save css-cherry
```

## Usage

After installation, you can then import the SCSS into your project sourcing from your `node_modules` directory:

```scss
@import "../node_modules/css-cherry/cherry.scss";
```

## Browser Support

Cherry uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Cherry is compatible with **recent** versions of:

* Chrome
* Edge
* Explorer 10+ (partially supported)
* Firefox
* Opera
* Safari

## Copyright and license

Copyright 2019 Ricky Boyce. Code released under [the MIT license](https://github.com/boycce/cherry/blob/master/LICENSE).
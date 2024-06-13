![](./assets/imgs/cherry.jpg)

[![NPM](https://img.shields.io/npm/v/cherry.svg)](https://www.npmjs.com/package/cherry) [![Build Status](https://travis-ci.com/boycce/cherry.svg?branch=master)](https://app.travis-ci.com/github/boycce/cherry)

## Install

This repository is distributed with NPM. After installing NPM, you can install Cherry CSS via:

```sh
npm install --save cherry
```

## Version

- `^1.0` has been rewritten to use Dart SASS
- `^0.1` uses node-sass

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

## Changes v1.0.3

1. The toggle styling has changed
2. styling variables for checkboxes and radios have changed

### Changed form variables
```scss
$forms: (
  "variable-color" // defaulted to `darken("input-background"), 12%`, this is now transparent
)
```

### Removed form variables
```scss
$forms: (
  // Checkbox/radio
  "checkbox-border-width" // renamed to "variable-border-width"
  "checkbox-border-radius" // renamed to "variable-border-radius"
  "checkbox-font-family" // renamed to "variable-font-family"
  "checkbox-font-size" // renamed to "variable-font-size"
  "checkbox-font-weight" // renamed to "variable-font-weight"
  "checkbox-letter-spacing" // renamed to "variable-letter-spacing"
  "checkbox-text-transform" // renamed to "variable-text-transform"
  "checkbox-padding-left" // renamed to "variable-padding-left"
  "checkbox-padding-right" // renamed to "variable-padding-right"
)
```

### Added form variables
```scss
$forms: (
  // Toggle/Checkbox/Radio
  "variable-color--active":        map-get($form, "variable-color--active")
  "variable-background":           map-get($form, "variable-background"),
  "variable-background--active":   map-get($form, "variable-background--active"),
  "variable-border-color":         map-get($form, "variable-border-color"),
  "variable-border-color--active": map-get($form, "variable-border-color--active"),
  // Checkbox 
  "checkbox-stroke-width":         8,
  // Toggle
  "toggle-inner-space":            4px,
  "toggle-color":                  map-get($form, "variable-border-color")
  "toggle-color--active":          map-get($form, "variable-color--active")
  "toggle-background":             map-get($form, "variable-background")
  "toggle-background--active":     map-get($form, "variable-background--active")
  "toggle-border-color":           map-get($form, "variable-border-color")
  "toggle-border-color--active":   map-get($form, "variable-border-color--active")
  "toggle-border-width":           map-get($form, "variable-border-width")
)
```

## Special Thanks

[Willy Blandin](https://github.com/blandinw)
[The Bulma Project](https://github.com/jgthms/bulma)

## Copyright and license

Copyright 2019 Ricky Boyce. Code released under [the MIT license](https://github.com/boycce/cherry/blob/master/LICENSE).

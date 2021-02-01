---
title: Elements
nav_order: 5
---

# Elements

### Variables

You can use these variables to customize these elements. Simply set these variables before importing Cherry.

#### Buttons

Variable | Default value | Computed value
- | - | -
`$btn-background-color`   | `$primary` | `hsl(259, 100%, 67%)`
`$btn-background-image`   | `null` |
`$btn-border-color`       | `null` |
`$btn-border-radius`      | `5px` |
`$btn-border-width`       | `2px` |
`$btn-box-shadow`         | `none` |
`$btn-box-shadow--active` | `$btn-box-shadow` | `0 0 10px 0px rgba(0, 0, 0, 0.05)`
`$btn-font-family`        | `$body-font-family` | `Open Sans, sans-serif`
`$btn-font-size`          | `14px` |
`$btn-font-weight`        | `600` |
`$btn-icon-size`          | `1.3em` |
`$btn-icon-margin`        | `0.4em` |
`$btn-padding`            | `12px 31px` |
`$btn-min-height`         | `0` |
`$btns-margin-right`      | `1rem` |
`$btns-margin-bottom`     | `1.5rem` |
You can add additional button colors which are avaliable via .btn-{name}
`$custom-colors`          | `e.g. ("{name}": (#000, #fff), ...)` |
You can add additional button color gradients which are avaliable via .btn-{name}
`$custom-gradients`       | `e.g. ("{name}": (160deg, #555, #333, #000), ...) ` |

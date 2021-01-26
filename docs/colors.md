---
title: Colors
nav_order: 2
---

# Colors

### Variables

You can use these variables to customize these elements. Simply set these variables before importing Cherry.

#### Initial colors

Variable | Default value
- | -
`$black`            | `hsl(0, 0%, 0%)`
`$black-light`      | `hsl(0, 0%, 7%)`
`$black-lighter`    | `hsl(0, 0%, 13%)`
`$grey`             | `hsl(0, 0%, 27%)`
`$grey-light`       | `hsl(0, 0%, 47%)`
`$grey-lighter`     | `hsl(0, 0%, 73%)`
`$grey-lightest`    | `hsl(0, 0%, 93%)`
`$white-darker`     | `hsl(0, 0%, 96%)`
`$white-dark`       | `hsl(0, 0%, 98%)`
`$white`            | `hsl(0, 0%, 100%)`
`$orange`           | `hsl(14,  100%, 53%)`
`$yellow`           | `hsl(48,  100%, 67%)`
`$green`            | `hsl(141, 53%,  53%)`
`$turquoise`        | `hsl(171, 100%, 41%)`
`$cyan`             | `hsl(204, 71%,  53%)`
`$blue`             | `hsl(217, 71%,  53%)`
`$violet`           | `hsl(259, 100%, 67%)`
`$purple`           | `hsl(271, 100%, 71%)`
`$red`              | `hsl(348, 86%, 61%)`

#### Derived app colors

Variable | Default value | Computed value
- | - | -
`$primary`          | `$violet`      | `hsl(259, 100%, 67%)`
`$secondary`        | `$blue`        | `hsl(217, 71%,  53%)`
`$success`          | `$green`       | `hsl(141, 53%,  53%)`
`$info`             | `$blue`        | `hsl(217, 71%,  53%)`
`$warning`          | `$yellow`      | `hsl(48,  100%, 67%)`
`$danger`           | `$red`         | `hsl(348, 86%, 61%)`
`$text`             | `$black-light` | `hsl(0, 0%, 7%)`
`$text-light`       | `$grey`        | `hsl(0, 0%, 27%)`
`$text-lighter`     | `$grey-light`  | `hsl(0, 0%, 47%)`
`$text-strong`      | `$black`       | `hsl(0, 0%, 0%)`
`$link`             | `$black`       | `hsl(0, 0%, 0%)`
`$link--focus`      | `$blue`        | `hsl(217, 71%,  53%)`
`$link--hover`      | `$blue`        | `hsl(217, 71%,  53%)`
You can also pass a map of custom colors | |
`$custom-colors`    | `e.g. (cherry: (red, findColorInvert(red)), ..)` | ..

#### Derived variations

Todo: fully intergated these into the a color, background, system

Variable | Default value | Computed value
- | - | -
`$primary-invert`   | `findColorInvert($primary)` | ..
`$primary-light`    | `findLightColor($primary)` | ..
`$primary-dark`     | `findDarkColor($primary)` | ..
`$secondary-invert` | `findColorInvert($secondary)` | ..
`$secondary-light`  | `findLightColor($secondary)` | ..
`$secondary-dark`   | `findDarkColor($secondary)` | ..
`$success-invert`   | `findColorInvert($success)` | ..
`$success-light`    | `findLightColor($success)` | ..
`$success-dark`     | `findDarkColor($success)` | ..
`$info-invert`      | `findColorInvert($info)` | ..
`$info-light`       | `findLightColor($info)` | ..
`$info-dark`        | `findDarkColor($info)` | ..
`$warning-invert`   | `findColorInvert($warning)` | ..
`$warning-light`    | `findLightColor($warning)` | ..
`$warning-dark`     | `findDarkColor($warning)` | ..
`$danger-invert`    | `findColorInvert($danger)` | ..
`$danger-light`     | `findLightColor($danger)` | ..
`$danger-dark`      | `findDarkColor($danger)` | ..

`$orange-invert`    | `findColorInvert($orange)` | ..
`$yellow-invert`    | `findColorInvert($yellow)` | ..
`$green-invert`     | `findColorInvert($green)` | ..
`$turquoise-invert` | `findColorInvert($turquoise)` | ..
`$cyan-invert`      | `findColorInvert($cyan)` | ..
`$blue-invert`      | `findColorInvert($blue)` | ..
`$purple-invert`    | `findColorInvert($purple)` | ..
`$red-invert`       | `findColorInvert($red)` | ..

#### Custom colors

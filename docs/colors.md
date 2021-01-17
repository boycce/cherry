---
title: Colors
nav_order: 2
---

# Colors

## Variables

You can use these variables to customize these elements. Simply set these variables before importing Cherry.

#### Initial colors

Variable | Default value
- | -
`$black`            | `hsl(0, 0%, 0%)`
`$black-light`      | `hsl(0, 0%, 7%)`
`$black-lighter`    | `hsl(0, 0%, 13%)`
 |
`$grey`             | `hsl(0, 0%, 27%)`
`$grey-light`       | `hsl(0, 0%, 47%)`
`$grey-lighter`     | `hsl(0, 0%, 73%)`
`$grey-lightest`    | `hsl(0, 0%, 93%)`
 |
`$orange`           | `hsl(14,  100%, 53%)`
`$yellow`           | `hsl(48,  100%, 67%)`
`$green`            | `hsl(141, 53%,  53%)`
`$turquoise`        | `hsl(171, 100%, 41%)`
`$cyan`             | `hsl(204, 71%,  53%)`
`$blue`             | `hsl(217, 71%,  53%)`
`$purple`           | `hsl(271, 100%, 71%)`
`$red`              | `hsl(348, 86%, 61%)`

#### Derived colors

Variable | Default value | Computed value
- | - | -
`$primary`          | `$purple` | ..
`$secondary`        | `$blue` | ..
`$success`          | `$green` | ..
`$info`             | `$blue` | ..
`$warning`          | `$yellow` | ..
`$danger`           | `$red` | ..
 | |
`$text`             | `$black-light` | ..
`$text-light`       | `$grey` | ..
`$text-lighter`     | `$grey-light` | ..
`$text-strong`      | `$black` | ..
`$link`             | `$black` | ..
`$link-focus`       | `$blue` | ..
`$link-hover`       | `$blue` | ..

#### Computed colors

Variable | Default value | Computed value
- | - | -
`$primary-light`    | `findLightColor($primary)` | ..
`$secondary-dark`   | `findDarkColor($secondary)` | ..
`$secondary-light`  | `findLightColor($secondary)` | ..
`$primary-dark`     | `findDarkColor($primary)` | ..
`$success-light`    | `findLightColor($success)` | ..
`$success-dark`     | `findDarkColor($success)` | ..
`$info-light`       | `findLightColor($info)` | ..
`$info-dark`        | `findDarkColor($info)` | ..
`$warning-light`    | `findLightColor($warning)` | ..
`$warning-dark`     | `findDarkColor($warning)` | ..
`$danger-light`     | `findLightColor($danger)` | ..
`$danger-dark`      | `findDarkColor($danger)` | ..

---
title: Base
nav_order: 2
---

# Base variables

You can use these variables to customize these elements. Simply set these variables before importing Cherry.

#### Initial colours

Variable | Default value | Computed value
- | - | -
`$black`            | `hsl(0, 0%, 0%)` | same as default
`$black-light`      | `hsl(0, 0%, 7%)` | same as default
`$black-lighter`    | `hsl(0, 0%, 13%)` | same as default
 | |
`$grey`             | `hsl(0, 0%, 27%)` | same as default
`$grey-light`       | `hsl(0, 0%, 47%)` | same as default
`$grey-lighter`     | `hsl(0, 0%, 73%)` | same as default
`$grey-lightest`    | `hsl(0, 0%, 93%)` | same as default
 | |
`$orange`           | `hsl(14,  100%, 53%)` | same as default
`$yellow`           | `hsl(48,  100%, 67%)` | same as default
`$green`            | `hsl(141, 53%,  53%)` | same as default
`$turquoise`        | `hsl(171, 100%, 41%)` | same as default
`$cyan`             | `hsl(204, 71%,  53%)` | same as default
`$blue`             | `hsl(217, 71%,  53%)` | same as default
`$purple`           | `hsl(271, 100%, 71%)` | same as default
`$red`              | `hsl(348, 86%, 61%)` | same as default

#### Application colours

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

#### Derived colours

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

#### Fonts

Variable | Default value | Computed value
- | - | -
`$family-primary`   | `Open Sans, sans-serif` | same as default
`$family-secondary` | `Open Sans, sans-serif` | same as default
`$family-code`      | `monospace` | same as default


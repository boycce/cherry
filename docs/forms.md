---
title: Forms
nav_order: 4
---

# Forms

### Variables

To customise these variables you can do so via the following SASS maps:

```sass
$form: (
  "input-background": #fff,
  //..
);

// You can also style a second set of form elements which will be avalialble under the class `.form-2`
$form-2: (
  "input-background": #000,
  //..
);
```

#### Error

Variable | Default value | Computed value
- | - | -
`error-font-size` | `0.85rem` |

#### Input

Variable | Default value | Computed value
- | - | -
`input-background`            | `#fdfdfd`           |
`input-background--active`    | input-background    | `#fdfdfd`
`input-background--invalid`   | input-background    | `#fdfdfd`
`input-border-color`          | `#efefef`           |
`input-border-color--active`  | `$primary`          | `hsl(259, 100%, 67%)`
`input-border-color--invalid` | `$danger`           | `hsl(348, 86%, 61%)`
`input-border-width`          | `2px`               |
`input-color`                 | `$text`             | `hsl(0, 0%, 7%)`
`input-color--invalid`        | `$text`             | `hsl(0, 0%, 7%)`
`input-font-family`           | `$body-font-family` | `Open Sans, sans-serif`
`input-font-size`             | `0.95rem`           |
`input-font-weight`           | `inherit`           |
`input-margin-bottom`         | `1.5rem`            |
`input-padding`               | `13px 19px`         |
`input-border-radius`         | `4px`               |
`input-placeholder-color`     | `rgba($text, 0.5)`  | ..

#### Label

Variable | Default value | Computed value
- | - | -
`label-color`            | `$text-light` | `hsl(0, 0%, 27%)`
`label-font-size`        | `0.85rem` |

#### Textarea

Variable | Default value | Computed value
- | - | -
`textarea-padding`       | `input-padding` | `13px 19px`
`textarea-min-height`    | `7em` |

#### Toggle / Checkbox/ Radio

Variable | Default value | Computed value
- | - | -
`checkbox-height`        | `20px`                           |
`checkbox-inner-height`  | `10px`                           |
`checkbox-padding-left`  | `12px`                           |
`checkbox-padding-right` | `16px`                           |
`toggle-height`          | `1.8em`                          |
`toggle-width`           | `toggle-height * 1.8`            | `3.24em`
`toggle-color`           | `darken(input-background, 10%)`  | ..
`toggle-color--active`   | `input-border-color--active`     | `hsl(259, 100%, 67%)`

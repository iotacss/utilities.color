**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Color Utility #

The color utility contains helper classes for the color CSS property.


### Installation ###

```
npm install --save iotacss-utils-color
```


### Options ###

```sass
$iota-utils-color-namespace : 'color-' !default;

$iota-utils-color-names     : () !default;
```


### Example ###

```sass
$iota-color-names: (
  white: #FFFFFF,
  black: #000000
);
```

It will generate:

```css
.u-color-white {
  color: #FFFFFF !important;
}

.u-color-black {
  color: #000000 !important;
}
```

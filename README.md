# Color Utility #

The color utility contains helper classes for the color CSS property.


### Installation ###

```
npm install --save iotacss-color
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)


### Options ###

```
$iota-color-namespace : 'color-' !default;
$iota-color-names     : () !default;
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

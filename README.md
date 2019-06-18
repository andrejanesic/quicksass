# Quick Sass

Highly customizable and very lightweight Sass framework for generating helper classes. Inspired by Bootstrap and PureCSS.

```
│   .gitignore
│   package.json   .......... npm package file
│   quicksass.scss .......... Imports all partials
│   README.md
│   
└───src
        _border.scss ........ Creates helper classes for border radius
        _breakpoints.scss ... Mixin for responsive media query breakpoints
        _colors.scss ........ Creates helper classes for text and background color
        _display.scss ....... Creates helper classes for responsive display property
        _size.scss .......... Creates helper classes for responsive element width and height
        _typography.scss .... Creates helper classes for responsive text sizes
        _whitespace.scss .... Creates helper classes for props such as padding and margin
```

## How to use

`Git clone` into your project folder. Simply import `quicksass` if you need all modules, or import them partially from `src`. Make sure to check whether the module requires `breakpoints` *(most responsive classes do!)*.

## Word of warning

The file can get **bigger** if a lot of customization is added. Make sure to be rational with the amount of helper classes (don't add unnecessary customization options to `values`) and also **purge** any unused CSS rules.
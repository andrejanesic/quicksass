# Quick Sass

Highly customizable and very lightweight Sass framework for generating helper classes. Inspired by Bootstrap and PureCSS.

```
│   .gitignore
│   package.json   .......... npm package file
│   quicksass.scss .......... Imports all partials
│   README.md
│   
└───src
        _breakpoints.scss ... Mixin for responsive media query breakpoints
        _colors.scss ........ Creates helper classes for text and background color
        _display.scss ....... Creates helper classes for responsive display property
        _typography.scss .... Creates helper classes for responsive text sizes
        _values.scss ........ Default values used by other partials
        _whitespace.scss .... Creates helper classes for props such as padding and margin
```

## Word of warning

The file can get **bigger** if a lot of customization is added. Make sure to be rational with your tools and also **purge** any unused CSS rules.
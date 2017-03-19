[![Build Status](https://travis-ci.org/JasonShin/postcss-korean-stylesheets.svg?branch=master)](https://travis-ci.org/JasonShin/postcss-korean-stylesheets)

[PostCSS] plugin for writing Korean Stylesheets.

[PostCSS]: https://github.com/postcss/postcss

send your ideas to ```visualbbasic@gmail.com```

## Korean syntax
```css
.foo {
    ㅋ: 9999;
    background-color: kimchi;
    color: 주;
    color: 노;
    color: 초;
    color: 파;
    color: 남;
    color: 보;
    color: 검;
    color: 흰;
    color: 갈;
}
```

## CSS output
```css
.foo {
    z-index: 9999;
    background-color: red;
    color: orange;
    color: yellow;
    color: green;
    color: blue;
    color: darkblue;
    color: purple;
    color: black;
    color: white;
    color: brown;
}
```

## Usage

```js
postcss([ require('postcss-korean-stylesheets') ])
```

See [PostCSS] docs for examples for your environment.

## Find this plugin at
http://postcss.parts/tag/fun

## Thanks to

Inspiration from [Canadian Stylesheets](https://github.com/chancancode/postcss-canadian-stylesheets) and chats with [@darylljann](https://twitter.com/darylljann)

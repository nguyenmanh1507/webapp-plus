# Webapp Plus

This repo clone from [webapp](https://github.com/yeoman/generator-webapp) with some modify.

## Differences from Yo Webapp

* Using PostCSS instead of SASS.
* Using Jade templates engine instead of plain HTML.

## Addition Gulp plugins

* [gulp-postcss](https://www.npmjs.com/package/gulp-postcss/): gulp plugin to pipe CSS through several processors, but parse CSS only once.
* [precss](https://github.com/jonathantneal/precss): Use Sass-like markup in your CSS.

## PostCSS plugins

* [autoprefixer](https://github.com/postcss/autoprefixer): Parse CSS and add vendor prefixes to rules by Can I Use.
* [postcss-bem](https://github.com/ileri/postcss-bem): PostCSS plugin implementing BEM as at-rules.
* [cssnano](https://github.com/ben-eb/cssnano): A modular minifier, built on top of the PostCSS ecosystem.
* [stylelint](https://github.com/stylelint/stylelint): A mighty, modern CSS linter that helps you enforce consistent conventions and avoid errors in your stylesheets (not use at moment).
* [postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician): Magically generate all the __@font-face__ rules.
* [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem): A plugin for PostCSS that generates rem units from pixel units.
* [postcss-at2x](https://github.com/simonsmith/postcss-at2x): A port of rework-at2x with some extra touches.
* [postcss-custom-media](https://github.com/postcss/postcss-custom-media): PostCSS plugin to transform W3C CSS Custom Media Queries syntax to more compatible CSS.

Install once:

```
npm i -D gulp-postcss precss autoprefixer postcss-bem cssnano stylelint postcss-font-magician postcss-pxtorem postcss-at2x postcss-custom-media
```

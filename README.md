RESET
=====

Minimal reset CSS

Install
-------

`npm install dam-reset --save`

Use
---

1. At the top of your stylesheet add
```css
@import "dam-reset";
```
2. Use any preprocessor that supports import
[postcss-import](https://github.com/postcss/postcss-import)
[rework-npm](https://github.com/reworkcss/rework-npm)
etc.
3. Compile
4. Your compiled stylesheet will add this minimal reset added
```css
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
```

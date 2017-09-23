# PostCSS Consistent Space [![Build Status][ci-img]][ci]

Maintain consistent margin and padding spaces thorough your project

[PostCSS]: https://github.com/postcss/postcss
[ci-img]:  https://travis-ci.org/DimitrisNL/postcss-consistent-space.svg
[ci]:      https://travis-ci.org/DimitrisNL/postcss-consistent-space

```css
.foo {
    @space margin 2 3;
}
```

```css
.foo {
  margin: 16px 24px;
}
```

## Usage

No options - fallback **8 pixel** grid
```js
postcss([ require('postcss-consistent-space') ])
```

or with props
```js
postcss([ require('postcss-consistent-space') ])
        ({
            base: 4,
            unit: 'em',
        }),
```

See [PostCSS] docs for examples for your environment.
# css-scale
[![NPM version][npm-image]][npm-url]
[![Downloads][downloads-image]][downloads-url]

Scalar CSS variables. Useful to quickly prototype interfaces using consistent
values. Extracted from [gravitons](http://jxnblk.com/gravitons).

## Installation
```sh
$ npm install css-scale
```

## Usage
With [sheetify](https://github.com/sheetify/sheetify) installed do:
```css
@import 'css-scale';

h1 {
  font-size: var(--h1);
}

.title {
  padding: var(--s2);
}
```

## API
### s{1..4}
A size value in `rem`. Useful for setting margins, offsets and other sizes.

### h{1..6}
A heading value in `rem`. Useful for setting font-sizes and line-heights.

## See Also
- [css-wipe](https://github.com/sheetify/css-wipe)
- [sheetify](https://github.com/sheetify/sheetify)

## License
[MIT](https://tldrlegal.com/license/mit-license)

[npm-image]: https://img.shields.io/npm/v/css-scale.svg?style=flat-square
[npm-url]: https://npmjs.org/package/css-scale
[downloads-image]: http://img.shields.io/npm/dm/css-scale.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/css-scale
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[standard-url]: https://github.com/feross/standard

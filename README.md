[![npm](https://img.shields.io/npm/v/is-valid-acn.svg)](https://www.npmjs.com/package/is-valid-acn) ![downloads](https://img.shields.io/npm/dt/is-valid-acn.svg) [![tested with jest](https://img.shields.io/badge/tested_with-jest-99424f.svg)](https://github.com/facebook/jest)

# is-valid-acn
Check if a number is a valid Australian Company Number (ACN).

## tl;dr
* Install by executing `npm install is-valid-acn` or `yarn add is-valid-acn`.
* Import by adding `import isValidACN from 'is-valid-acn'`.
* Use it by writing `const valid = isValidACN('010499966')`

## Examples

```js
> isValidACN('010499966');
< true

> isValidACN('010 499 966');
< true

> isValidACN('010-499-966');
< true
```

## License

The MIT License.

## Author

<table>
  <tr>
    <td>
      <img src="https://github.com/wojtekmaj.png?s=100" width="100">
    </td>
    <td>
      Wojciech Maj<br />
      <a href="mailto:kontakt@wojtekmaj.pl">kontakt@wojtekmaj.pl</a><br />
      <a href="http://wojtekmaj.pl">http://wojtekmaj.pl</a>
    </td>
  </tr>
</table>

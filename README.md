# Yandex+ Property Order

[![npm version][npm-img]][npm-url]
[![github issues][issues-img]][issues-url]

A [stylelint][] config that sorts CSS properties way [csscomb.js Yandex preset][csscomb-yandex].

This package is based on [stylelint-order-config-yandex][], but it has not been updated for a long time due to the lack of updates in the configurations for csscomb.js. This configuration will be maximally supported, especially when new css properties appear, for example, support for grid properties has already been added.

## Usage

1.  Add [stylelint][], [stylelint-order][] and this package to your project:
    ```sh
    npm install --save-dev stylelint stylelint-order stylelint-config-yandex-plus-order
    ```
2.  Configure your stylelint configuration file to extend this package:
    ```js
    module.exports = {
      extends: ['stylelint-config-yandex-plus-order'],
      rules: {
        // Add overrides and additional rules here
      }
    }
    ```

[npm-url]: https://www.npmjs.com/package/stylelint-config-yandex-plus-order
[npm-img]: https://img.shields.io/npm/v/stylelint-config-yandex-plus-order.svg?style=flat
[npm-dls]: https://img.shields.io/npm/dt/stylelint-config-yandex-plus-order.svg?style=flat
[issues-url]: https://github.com/maximpostnikov/stylelint-config-yandex-plus-order/issues
[issues-img]: https://img.shields.io/github/issues/maximpostnikov/stylelint-config-yandex-plus-order.svg?style=flat
[stylelint]: https://github.com/stylelint/stylelint
[stylelint-order]: https://github.com/hudochenkov/stylelint-order
[csscomb-yandex]: https://github.com/csscomb/csscomb.js/blob/dev/config/yandex.json
[stylelint-order-config-yandex]: https://github.com/d4rkcr0w/stylelint-order-config/tree/master/packages/stylelint-order-config-yandex

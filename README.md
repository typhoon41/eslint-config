# @typhoon41/eslint-config

> Strict, shareable config for JS/TS projects usint ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html).

To see the rules that this config uses, please read the [config itself](./index.js).

## Installation

```
$ npm install --save-dev eslint @typhoon41/eslint-config
```

## Usage

Once the `@typhoon41/eslint-config` package is installed, you can use it by specifying `@typhoon41/eslint-config` in the [`extends`](http://eslint.org/docs/user-guide/configuring#extending-configuration-files) section of your [ESLint configuration](http://eslint.org/docs/user-guide/configuring).

```js
{
  "extends": "@typhoon41/eslint-config",
  "rules": {
    // Additional, per-project rules...
  }
}
```

## License

Apache-2 © Nikola Dragićević
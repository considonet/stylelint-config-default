# @considonet/stylelint-config-default

> Default main [`stylelint`](https://github.com/stylelint/stylelint) ruleset for ConsidoNet projects

## What's inside?

Includes:
- [`@considonet/stylelint-config-scss`](https://github.com/considonet/stylelint-config-scss) - General rules for SCSS code
- [`@considonet/stylelint-config-bem`](https://github.com/considonet/stylelint-config-bem) - BEM validation profile
- [`@considonet/stylelint-config-order`](https://github.com/considonet/stylelint-config-order) - Properties ordering ruleset

## Installation

Using npm:

```sh
npm install --save-dev @considonet/stylelint-config-default
```

or using yarn:

```sh
yarn add @considonet/stylelint-config-default --dev
```

## Usage

In your .stylelintrc.js file extend your config:

```json
{ 
  "extends": "@considonet/stylelint-config-default"
}
```

Of course feel free to extend or overwrite this config by adding new rules. See [`stylelint` documentation](https://stylelint.io/user-guide/configuration) and [available rules](https://stylelint.io/user-guide/rules) for more info.

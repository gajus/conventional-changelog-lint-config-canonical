# conventional-changelog-lint-config-canonical

A shareable [`conventional-changelog-lint`](https://github.com/marionebl/conventional-changelog-lint) configuration for Canonical commit convention.

## Installation

This project uses [node](http://nodejs.org/) and [npm](https://npmjs.com/).

```sh
npm install conventional-changelog-lint-config-canonical conventional-changelog-lint --save-dev
```

## Usage

The `conventional-changelog-lint` command line interface reads `.conventional-changelog-lintrc`. Use `extends` property to configure `conventional-changelog-lint` to use `conventional-changelog-lint-config-canonical`.

```json
{
  "extends": [
    "canonical"
  ]
}
```

## Rules

* Refer to [`./conventional-changelog-lintrc.json`](./conventional-changelog-lintrc.json) to see the configuration.
* Refer to [`conventional-changelog-lint#rules`](./https://github.com/marionebl/conventional-changelog-lint/blob/master/documentation/rules.md) to learn the available configurations.

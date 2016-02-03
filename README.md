# eslint-config-testpilot

Shared ESLint config for Test Pilot repos.

## Installation:

Unfortunately, it doesn't look like you can obscure the nested dependencies into the external
config. So for now you need to install the `eslint-config-testpilot` config, the [`eslint-config-airbnb`](https://www.npmjs.com/package/eslint-config-airbnb) config, and the [`babel-eslint`](https://www.npmjs.com/package/babel-eslint) parser:

```sh
$ npm i -D eslint-config-testpilot eslint-config-airbnb babel-eslint
```

## Usage:

Simply create an .eslintrc file and extend the fancy "testpilot" config:

```yaml
extends: testpilot
```

# @rasabb/eslint-config

> [Shareable ESLint config](https://eslint.org/docs/developer-guide/shareable-configs.html) inspired heavily by [eslint-config-google](https://github.com/google/eslint-config-google) and moderately by [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb).

## Installation

```bash
yarn add --dev eslint "@rasabb/eslint-config@*"
```

## Usage

`.eslintrc.json`:

```json5
{
  "extends": [
    "@rasabb/eslint-config"
  ],
  "env": {
    "browser": true,
    "node": true
  },
  "rules": {
    // Project-specific overrides...
  }
}
```

## License

MIT

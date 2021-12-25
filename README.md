# Mitz ESLint & Prettier Config

## Installation
```sh
npm install -D @mitz/eslint-config
```

## Usage

In `eslintrc.json`:

```js
{
  "extends": "@mitz/eslint-config",
  "parserOptions": {
    "project": ["tsconfig.json", "test/tsconfig.json"]
  }
}
```


## License

Apache 2.0

# @sitek94/prettier-config

My shareable Prettier config.

## Usage

In `package.json`:

```json
{
  "name": "my-cool-library",
  "version": "1.0.0",
  "prettier": "@sitek94/prettier-config"
}
```

If you want to extend it:

```js
module.exports = {
  ...require('@sitek94/prettier-config'),
  semi: false,
}
```

## Resources

- [Prettier: Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)

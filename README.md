# @sitek94/prettier-config

My shareable Prettier config.

## Usage

### Install

Config only:

```
npm i -D @sitek94/prettier-config
```

Config and prettier:

```
npm i -D prettier @sitek94/prettier-config
```

### Reference config

In `package.json`:

```json
{
  "name": "my-cool-library",
  "version": "1.0.0",
  "prettier": "@sitek94/prettier-config"
}
```

Or, if you want to extend it:

```js
module.exports = {
  ...require('@sitek94/prettier-config'),
  semi: false,
}
```

## Resources

- [Prettier: Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)

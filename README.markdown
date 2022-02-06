# @ghslp/stylelint-config

Shared [Stylelint](https://stylelint.io/) config for personal projects.

## How to use

### Install

```sh
npm install @ghslp/stylelint-config --dev
npx install-peerdeps @ghslp/stylelint-config --dev
```

### Add to Stylelint config

Create a `stylelint.config.js` containing (at least) the following:

```js
const stylelintConfig = {
  extends: ["@ghslp/stylelint-config"],
};

module.exports = stylelintConfig;
```

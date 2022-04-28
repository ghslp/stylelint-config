# @grantheaslip/stylelint-config

Shared [Stylelint](https://stylelint.io/) config for personal projects.

## How to use

### Install

```sh
npm install @grantheaslip/stylelint-config --dev
npx install-peerdeps @grantheaslip/stylelint-config --dev
```

### Add to Stylelint config

Create a `stylelint.config.js` containing (at least) the following:

```js
const stylelintConfig = {
  extends: ["@grantheaslip/stylelint-config"],
};

module.exports = stylelintConfig;
```

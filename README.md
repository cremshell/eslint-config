# @cremshell/eslint-config

My custom ESLint config for React + TypeScript projects.

## Installation

```bash
npm install -D @cremshell/eslint-config \
  eslint \
  @typescript-eslint/eslint-plugin \
  @typescript-eslint/parser \
  eslint-plugin-react \
  eslint-plugin-react-hooks \
  eslint-plugin-jsx-a11y \
  eslint-config-prettier
```

## Usage

In your .eslintrc.js:

```js
module.exports = {
  extends: ["@cremshell/eslint-config"],
};
```

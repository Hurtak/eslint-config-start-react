# eslint-config-start-react

- Slightly opinionated ESLint config that should be a good start for any [React](https://reactjs.org/) project.

## What it contains

- [react/recommended](https://github.com/jsx-eslint/eslint-plugin-react#recommended)
- [react-hooks/recommended](https://www.npmjs.com/package/eslint-plugin-react-hooks)
- [plugin:jsx-a11y/strict](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)

Check the full list of rules in [index.js](./index.js)

## Install

```shell
npm install --save-dev eslint-config-start-react
```

## Configure

Add this to your `.eslintrc` file:

```json
{
  "extends": [
    "start-react"
  ]
}
```

## List of `start` packages

- [eslint-config-start](https://github.com/Hurtak/eslint-config-start)
- [eslint-config-start-react](https://github.com/Hurtak/eslint-config-start-react)

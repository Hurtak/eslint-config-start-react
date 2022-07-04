# eslint-config-start-react

- Slightly opinionated ESLint config that should be a good start for any [React](https://reactjs.org/) project.

## What it contains

- [react/recommended](https://eslint.org/docs/latest/user-guide/configuring/configuration-files#using-eslintrecommended)
- [react-hooks/recommended](https://github.com/sindresorhus/eslint-plugin-unicorn)
- [plugin:jsx-a11y/strict](https://github.com/sindresorhus/eslint-plugin-unicorn)

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

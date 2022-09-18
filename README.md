# Eslint Config

This is my base eslint configuration that I use on all projects. For now I kept this to not be framework specific since I play with all types of frameworks.

## Installation

If you have a javascript/typescript project you can install and set up the config by running the following command:

```bash
yarn add -D @jrock2004/eslint-config @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier prettier typescript
```

Then add the following to your `package.json`:

```json
{
  "eslintConfig": {
    "extends": "@jrock2004/eslint-config"
  }
}
```

## CRA Installation

If you are building a react project with create-react-app you can use my CRA template to get started. You can install the template by running the following command:

```bash
yarn create react-app my-app --template @jrock2004/cra-template-a11y
```

Then cd into the project to finish setting up:

```bash
npx msw init public/ --save
```

# React Native Eslint Prettier Starter

## Create React Native Project

Reference [React Native CLI QuickStart](https://facebook.github.io/react-native/docs/getting-started)

```
npx react-native init YourProject
```

## ESLint

ESLint > 6 has error with `@react-native-community/eslint-config`. So install `eslint@5.16.0`.

```
yarn add eslint@5.16.0 --exact -D
```

Than's all.

`@react-native-community/eslint-config` already has options related to React Native.


## VSCode settings

.vscode/settings.json

```
{
  "editor.formatOnSave": true,
  // disable editor formatting, so eslint can handle it
  "[javascript]": {
    "editor.formatOnSave": false,
  },
  "typescript.validate.enable": false,
  "javascript.validate.enable": false,
  // available through eslint plugin in vscode
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
}
```

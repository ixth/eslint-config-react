# My ESLint Preferences for React projects

## Usage:

1. Install package:
```shell
#npm
npm install --save-dev git+ssh://git@github.com/ixth/eslint-config-react.git

# yarn
yarn add --dev git+ssh://git@github.com/ixth/eslint-config-react.git
```

2. Add config into `extends` section in `.eslintrc`:
```diff
     "extends": [
+         "@ixth/eslint-config-react",
          "some-other-config"
     ],
```

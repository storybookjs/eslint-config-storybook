# @storybook/eslint-config-storybook

Thin wrapper around our @storybook/linter-config package, because eslint really really likes this package name for discoverability.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```sh
# npm
npm install eslint --save-dev

# yarn
yarn add eslint --dev
```

Next, install `@storybook/eslint-config-storybook`:

```sh
# npm
npm install @storybook/eslint-config-storybook --save-dev

# yarn
yarn add @storybook/eslint-config-storybook --dev
```

## Usage

Add `@storybook/eslint-config-storybook` to the extends section of your `.eslintrc` configuration file.

```json
{
  "extends": ["@storybook/eslint-config-storybook"]
}
```

Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "react/prop-types": "off"
  }
}
```

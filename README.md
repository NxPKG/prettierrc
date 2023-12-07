# Nxpkg Prettier Config

[![npm](https://img.shields.io/npm/v/@nx-pkg/prettierrc.svg)](https://www.npmjs.com/package/@nx-pkg/prettierrc)
[![downloads](https://img.shields.io/npm/dt/@nx-pkg/prettierrc.svg)](https://www.npmjs.com/package/@nx-pkg/prettierrc)
[![build](https://travis-ci.org/nxpkg/prettierrc.svg?branch=master)](https://travis-ci.org/nxpkg/prettierrc)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

Prettier config for projects at Nxpkg.

## Usage

```
npm install --save-dev @nx-pkg/prettierrc
```

Then add this `prettier.config.js` to the project:

```js
module.exports = require('@nx-pkg/prettierrc')
```

## Making changes

```
npm link
cd <project>
npm link @nx-pkg/prettierrc
npm run prettier
```

## Publish a new version

Follow [semver](http://semver.org/). **Changing or adding a rule is a breaking change and requires a new major version**.

```
npm version major|minor|patch
git push
git push --tags
npm publish
```

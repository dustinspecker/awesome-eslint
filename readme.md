# Awesome ESLint [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="http://eslint.org/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Table of Contents

- [Configs](#configs)
- [Parsers](#parsers)
- [Plugins](#plugins)
 - [Frameworks and Libraries](#frameworks-and-libraries)
 - [Misc.](#misc)
 - [Practices](#practices)
 - [Style](#style)
- [Preconfigured Tools with ESLint Set up](#preconfigured-tools-with-eslint-set-up)
- [Tools](#tools)
- [Tutorials](#tutorials)

## Configs

 - [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide](https://github.com/airbnb/javascript)
 - [Canonical](https://github.com/gajus/eslint-config-canonical) – Shareable config for [Canonical style guide](https://github.com/gajus/canonical)
 - [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Shareable config for ESLint's default settings
 - [Google](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml)
 - [Shopify](https://github.com/Shopify/javascript/tree/master/packages/eslint-plugin-shopify) - Shareable config for [Shopify's style guide](https://github.com/Shopify/javascript)
 - [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard)
 - [XO](https://github.com/sindresorhus/eslint-config-xo) - Shareable config for [XO](https://github.com/sindresorhus/xo)

## Parsers

 - [Babel](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features

## Plugins

### Frameworks and Libraries

 - [Angular](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's Angular Styleguide](https://github.com/johnpapa/angular-styleguide)
 - [AVA](https://github.com/sindresorhus/eslint-plugin-ava) - Linting rules for AVA
 - [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone
 - [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine
 - [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments
 - [Lodash](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules
 - [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules
 - [Meteor](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules
 - [Mocha](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha
 - [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native nodejs driver linting rules
 - [Node](https://github.com/mysticatea/eslint-plugin-node) - Linting rules for Node.js (checking importing paths, ES syntax, ...)
 - [React](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX
 - [React Native](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules

### Misc.

 - [Babel](https://github.com/babel/eslint-plugin-babel) - Adds replacements for built-in rules to include Babel features
 - [Flow](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules
 - [import](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+  import/export syntax, and prevent issues with misspelling of file paths and import names
 - [Markdown](https://github.com/eslint/eslint-plugin-markdown) - Linting JavaScript in Markdown
 - [XO](https://github.com/sindresorhus/eslint-plugin-xo) - Various useful rules

### Practices

 - [Immutable](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript
 - [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`
 - [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
 - [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects

### Style

 - [filenames](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your javascript files
 - [import-order](https://github.com/jfmengels/eslint-plugin-import-order) - Enforce the order of import/require statements
 - [no-empty-blocks](https://github.com/alex-shnayder/eslint-plugin-no-empty-blocks) - Allows empty catch blocks, while disallowing other empty blocks

## Preconfigured Tools with ESLint Set up

 - [Node.js Standard Style](https://github.com/geek/node-style) - Node.js core config.
 - [Standard](https://github.com/feross/standard) - JavaScript Standard Style
 - [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️

## Tools

 - [eslint-cli](https://github.com/mysticatea/eslint-cli) - This is the `eslint` command that executes a local installed ESLint.
 - [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config
 - [eslint-nibble](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time

## Tutorials

 - [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin
 - [Lint Like It’s 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint
 - [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics
 - [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

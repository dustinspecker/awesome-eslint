# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://eslint.org/assets/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Contents

- [Configs](#configs)
  - [Configs by Well-Known Companies/Organizations](#configs-by-well-known-companiesorganizations)
  - [Other Prominent Configs (100 stars or so)](#other-prominent-configs-100-stars-or-so)
  - [Other Configs](#other-configs)
- [Preconfigured Configs with ESLint Set up](#preconfigured-configs-with-eslint-set-up)
- [Plugins](#plugins)
  - [Code Quality](#code-quality)
  - [Compatiblity](#compatiblity)
  - [Deprecation](#deprecation)
  - [Embedded](#embedded)
  - [Frameworks](#frameworks)
  - [Languages](#languages)
  - [Libraries](#libraries)
  - [Misc](#misc)
  - [Practices](#practices)
  - [Performance](#performance)
  - [Security](#security)
  - [Style](#style)
  - [Testing Tools](#testing-tools)
- [Parsers](#parsers)
- [Formatters](#formatters)
- [Globals](#globals)
- [Tools](#tools)
- [Developing for ESLint](#developing-for-eslint)
- [Tutorials](#tutorials)

## Configs

### Configs by Well-Known Companies/Organizations

- [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide](https://github.com/airbnb/javascript).
- [Airbnb-typescript](https://github.com/iamturns/eslint-config-airbnb-typescript) - Airbnb's ESLint config with TypeScript support.
- [Alloy](https://github.com/AlloyTeam/eslint-config-alloy) - Progressive ESLint config for your React/Vue/TypeScript projects.
- [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team.
- [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- [Google](https://github.com/google/eslint-config-google) - Shareable config for the [Google style](http://google.github.io/styleguide/javascriptguide.xml).
- [React App](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app) - Sharable config for [React](https://reactjs.org) projects.
- [Shopify](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md) - Shareable config for [Shopify's style guide](https://github.com/Shopify/javascript).
- [Wikimedia](https://github.com/wikimedia/eslint-config-wikimedia) - Shareable config for [Wikimedia's style guide](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by [MediaWiki](https://www.mediawiki.org/).

### Other Prominent Configs (100 stars or so)

- [Canonical](https://github.com/gajus/eslint-config-canonical) - Shareable config for [Canonical style guide](https://github.com/gajus/canonical).
- [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard).
- [XO](https://github.com/xojs/eslint-config-xo) - Shareable config for [XO](https://github.com/xojs/xo).

### Other Configs

- [Adjunct](https://github.com/davidjbradshaw/eslint-config-adjunct) - A reasonable collection of plugins to use alongside your main esLint configuration.
- [Ash-Nazg](https://github.com/brettz9/eslint-config-ash-nazg) - One config to rule them all!
- [Cecilia](https://github.com/SandroMiguel/eslint-config-cecilia) - ESLint configuration for awesome projects.
- [ES](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code.
- [Hardcore](https://github.com/EvgenyOrekhov/eslint-config-hardcore) - The most strict (but practical) ESLint config out there.
- [Problems](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
- [Supermind](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style.

## Preconfigured Configs with ESLint Set up

- [Node.js Standard Style](https://github.com/geek/node-style) - Node.js core config.
- [prettier-standard](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style.
- [Superlint](https://github.com/supermind/superlint) - JavaScript Supermind Style.
- [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️.
- [Zoe](https://github.com/jorgegonzalez/zoe) - Universal JavaScript linter and formatter.
- [Healthier](https://github.com/KidkArolis/healthier) - Code style agnostic version of Standard, perfect companion to Prettier.

## Plugins

### Code Quality

- [SonarJS](https://github.com/SonarSource/eslint-plugin-sonarjs) - Rules detecting bugs and suspicious patterns.
- [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules.

### Compatiblity

- [Compat](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatibility of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
- [ecmascript-compat](https://github.com/robatwilliams/es-compat) - Disable ECMAScript language features not supported by your browserslist targets.
- [es](https://github.com/mysticatea/eslint-plugin-es) - Disable specific ECMAScript language versions or individual features.
- [es5](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage).
- [ie11](https://github.com/Volox/eslint-plugin-ie11) - Detect unsupported ES6 features in IE11.

### Deprecation

- [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used.
- [deprecation](https://github.com/gund/eslint-plugin-deprecation) - Identifies use of
  jsdoc `@deprecated` functions.
- [disable](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments.

### Embedded

- [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags.
- [Markdown](https://github.com/eslint/eslint-plugin-markdown) - Linting for JavaScript inside of Markdown.

### Frameworks

- [AngularJS](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide).
- [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone.
- [Ember](https://github.com/netguru/eslint-plugin-ember) - Linting rules for Ember.
- [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) - Linting rules for hapi.
- [Meteor](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules.
- React
  - [JSX a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements.
  - [React](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX.
  - [React Hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - Linting rules for React Hooks.
  - [React Native](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules.
  - [React-Redux](https://github.com/DianaSuvorova/eslint-plugin-react-redux) - React-Redux specific linting rules.
- Vue
  - [VueJS](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS.
  - [VueJS Scoped CSS](https://github.com/future-architect/eslint-plugin-vue-scoped-css) - Plugin for Scoped CSS in VueJS.

### Languages

- [Coffee](https://github.com/aminland/eslint-plugin-coffee) - Enables linting CoffeeScript files with, with optional linting rules from the Coffeelint library.
- ES5
  - [Babel](https://github.com/babel/eslint-plugin-babel) - Adds replacements for built-in rules to include Babel features.
  - [import](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+  import/export syntax, and prevent issues with misspelling of file paths and import names.
- Flow
  - [Flow](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules.
  - [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin.
- JSON
  - [JSON](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files.
  - [JSON, package.json](https://github.com/Bkucera/eslint-plugin-json-format) - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
  - [JSON with Comments](https://github.com/ota-meshi/eslint-plugin-jsonc) - ESLint plugin for JSON, JSONC and JSON5.
- [Node](https://github.com/mysticatea/eslint-plugin-node) - Additional ESLint's rules for Node.js.
- [SQL](https://github.com/gajus/eslint-plugin-sql) - SQL linting rules for ESLint.
- [TypeScript](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin) - Linting rules for TypeScript.

### Libraries

- [GraphQL](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema.
- [jQuery](https://github.com/wikimedia/eslint-plugin-no-jquery) - Linting rules for jQuery, including versioned configs for deprecated features.
- [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments (including the JavaScript within `@example`).
- Lodash
  - [Lodash](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules.
  - [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules.
  - [Lodash template](https://github.com/ota-meshi/eslint-plugin-lodash-template) - Plugin for Lodash template/Underscore template.
  - [Microtemplates](https://github.com/platinumazure/eslint-plugin-microtemplates) (Used in Lodash and Underscore.js)
- [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native Node.js driver linting rules.
- [Ramda](https://github.com/ramda/eslint-plugin-ramda) - Ramda specific linting rules.
- [RequireJS](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS.

### Misc

- [CSS-modules](https://github.com/atfzl/eslint-plugin-css-modules) - Lint undefined or unused rules for css modules.
- [ESLint Comments](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.).
- [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins.
- [@mysticatea/eslint-plugin](https://github.com/mysticatea/eslint-plugin) - Misc. rules.
- [Notice](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too!
- [Only-Error](https://github.com/davidjbradshaw/eslint-plugin-only-error) - Convert all rules to errors.
- [Only-Warn](https://github.com/bfanger/eslint-plugin-only-warn) - Convert all rules to warnings.
- [PutOut](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout) - an ESLint plugin integrates [putout](https://github.com/coderaiser/putout) linter into ESLint.
- [TypeLint](https://github.com/yarax/typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.

### Practices

- [array-func](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.
- [arrow functions](https://github.com/getify/eslint-plugin-proper-arrows) - ESLint rules to ensure proper arrow function definitions.
- [boundaries](https://github.com/javierbrea/eslint-plugin-boundaries) - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
- [fp](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming.
- [functional](https://github.com/jonaskello/eslint-plugin-functional) - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
- [Immutable](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript.
- [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`.
- [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
- [no-loops](https://github.com/buildo/eslint-plugin-no-loops) - It's 2019 and you still use loops?
- [no-restricted-syntax](https://github.com/brettz9/eslint-plugin-query) - Show queried syntax's content in messages.
- [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects.
- [Promise](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises.
- [RegExp](https://github.com/ota-meshi/eslint-plugin-regexp) - ESLint plugin for finding regexp mistakes and style guide violations.
- [sort-keys-fix](https://github.com/leo-buneev/eslint-plugin-sort-keys-fix) - Adds fixer for ESLint `sort-keys` rule.
- [this](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`.
- [toplevel](https://github.com/HKalbasi/eslint-plugin-toplevel) - An eslint plugin for disallow side effect at module toplevel.

### Performance

- [DOM](https://github.com/amilajack/eslint-plugin-dom)
- [Optimize Regex](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals.
- Perf-Standard [plugin](https://github.com/Raynos/eslint-plugin-perf-standard) and [Config](https://github.com/Raynos/eslint-config-perf-standard)

### Security

- [no-secrets](https://github.com/nickdeis/eslint-plugin-no-secrets) - An eslint plugin that detects potential secrets/credentials.
- [no-unsanitized](https://github.com/mozilla/eslint-plugin-no-unsanitized) - Checks for `innerHTML`, `outerHTML`, etc.
- ScanJS [config](https://github.com/mozfreddyb/eslint-config-scanjs) and [plugin](https://github.com/mozfreddyb/eslint-plugin-scanjs-rules) - Security-related rules.
- [Security](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security.
- [xss](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production.

### Style

- [editorconfig](https://github.com/platinumazure/eslint-plugin-editorconfig) - Derive rules from [`.editorconfig`](https://editorconfig.org/)
- [filenames](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your JavaScript files.
- [Simple import sort](https://github.com/lydell/eslint-plugin-simple-import-sort) - Easy autofixable import sorting.
- [Switch case](https://github.com/lukeapage/eslint-plugin-switch-case) - Switch-case-specific linting rules for ESLint.

### Testing Tools

- [AVA](https://github.com/avajs/eslint-plugin-ava) - Linting rules for AVA.
- Chai
  - [expect practices](https://github.com/turbo87/eslint-plugin-chai-expect)
  - [with unused expressions](https://github.com/ihordiachenko/eslint-plugin-chai-friendly)
  - [permitted keywords](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords)
  - [with chai-as-promised plugin](https://github.com/fintechstudios/eslint-plugin-chai-as-promised)
  - [globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
- [Cucumber](https://github.com/darrinholst/eslint-plugin-cucumber) - Linting rules for Cucumber.
- [Cypress](https://github.com/cypress-io/eslint-plugin-cypress) - Linting rules for Cypress.
- [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine.
- Jest
  - [Enforcing practices](https://github.com/jest-community/eslint-plugin-jest) - Linting rules for Jest.
  - [Enforcing consistent formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) - Formatting rules for Jest.
  - [Jest-async](https://www.npmjs.com/package/eslint-plugin-jest-async) - Async linting rule for Jest.
  - [Jest-DOM](https://github.com/testing-library/eslint-plugin-jest-dom) - Linting rules for Jest-DOM.
- Mocha
  - [Enforcing practices](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha.
  - [Enforcing manageability](https://github.com/onechiporenko/eslint-plugin-mocha-cleanup/)
- [QUnit](https://github.com/platinumazure/eslint-plugin-qunit) - Linting rules for QUnit.
- [Testcafe](https://github.com/miherlosev/eslint-plugin-testcafe) - Linting rules for Testcafe.
- [Testing Library](https://github.com/testing-library/eslint-plugin-testing-library) - Linting rules for Testing Library.

## Parsers

- [Babel](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features.
- [TypeScript](https://github.com/typescript-eslint/typescript-eslint) - A TypeScript parser that produces output compatible with ESLint.
- [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules.

## Formatters

- [eslint-formatter-badger](https://github.com/brettz9/eslint-formatter-badger) - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
- [eslint-formatter-git-log](https://github.com/JamieMason/eslint-formatter-git-log) - ESLint Formatter featuring Git Author, Date, and Hash.
- [eslint-formatter-github](https://github.com/hipstersmoothie/eslint-formatter-github) - See ESLint errors and warnings directly in pull requests.
- [eslint-formatter-gitlab](https://gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
- [eslint-formatter-mo](https://github.com/fengzilong/eslint-formatter-mo) - Good-lookin' ESLint formatter and also for delightful reading experience.
- [eslint-formatter-summary-chart](https://github.com/davidjbradshaw/eslint-formatter-summary-chart) Format ESLint output into a bar chart.

## Globals

- [Restricted Globals](https://github.com/sidoshi/eslint-restricted-globals) - Expect `window` qualifier on globals that may otherwise be confusable as local variables.
- [ES and browser globals](https://github.com/sindresorhus/globals) (originally from ESLint)
- [chai globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)

## Tools

- [es-file-traverse](https://github.com/brettz9/es-file-traverse) - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
- [eslint-cli](https://github.com/eslint/eslint-cli) - This is the `eslint` command that executes a local installed ESLint.
- [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config.
- [eslint-index](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files.
- [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer) - Multiplex eslint results and merge results for common files.
- [eslint-nibble](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time.
- [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule.
- [eslint-watch](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode.
- [codacy-eslint](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint.
- [esprint](https://github.com/pinterest/esprint) - Run ESLint across multiple threads.

## Developing for ESLint

- [eslint-docs](https://github.com/j-f1/eslint-docs) - Keep your rule descriptions up-to-date across the repository.

## Tutorials

- [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
- [Lint Like It's 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
- [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics.
- [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint.
- [Plugin Module with Mixins](https://chrysanthium.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration.
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

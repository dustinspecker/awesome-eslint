# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://eslint.org/icon.svg" width="160" align="right" alt="eslint">](http://eslint.org)

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
  - [Compatibility](#compatibility)
  - [CSS in JS](#css-in-js)
  - [Deprecation](#deprecation)
  - [Embedded](#embedded)
  - [Frameworks](#frameworks)
  - [Languages and Environments](#languages-and-environments)
  - [Libraries](#libraries)
  - [Misc](#misc)
  - [Practices and Specific ES Features](#practices-and-specific-es-features)
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
- [Installation and Setup](#installation-and-setup)

## Configs

### Configs by Well-Known Companies/Organizations

- [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for [Airbnb's style guide](https://github.com/airbnb/javascript).
- [Airbnb-babel](https://github.com/davidjbradshaw/eslint-config-airbnb-babel) - Airbnb's ESLint config with Babel Support.
- [Alloy](https://github.com/AlloyTeam/eslint-config-alloy) - Progressive ESLint config for your React/Vue/TypeScript projects.
- [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team.
- [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- [Feedzai](https://github.com/feedzai/eslint-config-feedzai) - Feedzai's shareable config for JavaScript/React projects.
- [Shopify](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md) - Shareable config for [Shopify's style guide](https://github.com/Shopify/javascript).
- [Wikimedia](https://github.com/wikimedia/eslint-config-wikimedia) - Shareable config for [Wikimedia's style guide](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by [MediaWiki](https://www.mediawiki.org/).

### Other Prominent Configs (100 stars or so)

- [Auto](https://github.com/davidjbradshaw/eslint-config-auto) - Automatically configure ESLint based on your project's dependencies.
- [Canonical](https://github.com/gajus/eslint-config-canonical) - Shareable config for [Canonical style guide](https://github.com/gajus/canonical).
<!-- lint disable double-link -->
- [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript [Standard Style](https://github.com/feross/standard).
- [XO](https://github.com/xojs/eslint-config-xo) - Shareable config for [XO](https://github.com/xojs/xo).
- [Antfu Eslint Config](https://github.com/antfu/eslint-config) - Anthony's ESLint config preset.

### Other Configs

- [Adjunct](https://github.com/davidjbradshaw/eslint-config-adjunct) - A reasonable collection of plugins to use alongside your main ESLint configuration.
- [Ash-Nazg](https://github.com/brettz9/eslint-config-ash-nazg) - One config to rule them all!
- [Cecilia](https://github.com/SandroMiguel/eslint-config-cecilia) - ESLint configuration for awesome projects.
- [clean-typescript](https://github.com/cunarist/eslint-config-clean-typescript) - Enforce classic JavaScript featuress in TypeScript codebase by banning excessive keywords.
- [Hardcore](https://github.com/EvgenyOrekhov/eslint-config-hardcore) - The most strict (but practical) ESLint config out there.
- [Problems](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
- [Supermind](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style.
- [Sheriff](https://github.com/AndreaPontrandolfo/sheriff) - Comprehensive and highly opinionated Eslint configuration. Typescript oriented.

## Preconfigured Configs with ESLint Set up

- [Node.js Standard Style](https://github.com/geek/node-style) - Node.js core config.
- [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier) - Prettier config for ESlint maintained by Prettier team.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style.
- [Superlint](https://github.com/supermind/superlint) - JavaScript Supermind Style.
- [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️.

## Plugins

### Code Quality

- [depend](https://github.com/es-tooling/eslint-plugin-depend) - Helps detect dependency tree bloat and redundant polyfills.
- [GitHub](https://github.com/github/eslint-plugin-github) - Misc. rules from GitHub.
- [SonarJS](https://github.com/SonarSource/SonarJS/blob/master/packages/jsts/src/rules/README.md) - Rules detecting bugs and suspicious patterns.
- [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules.
- [@mysticatea/eslint-plugin](https://github.com/mysticatea/eslint-plugin) - Misc. rules.
- [@brettz9/eslint-plugin](https://github.com/brettz9/eslint-plugin) - Misc. rules. of `@mysticatea` without the personal config.
- [De Morgan](https://github.com/azat-io/eslint-plugin-de-morgan) - Transforms logical expressions in code to make them easier to understand.
- [eslint-plugin-code-complete](https://github.com/aryelu/eslint-plugin-code-complete) - A custom ESLint plugin that enforces principles of clean, maintainable software design — inspired by Code Complete.



### Compatibility

- [Compat](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatibility of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
- [ecmascript-compat](https://github.com/robatwilliams/es-compat) - Disable ECMAScript language features not supported by your browserslist targets.
- [es-x](https://github.com/eslint-community/eslint-plugin-es-x) - Disable specific ECMAScript language versions or individual features. Properly maintained fork of no longer maintained `eslint-plugin-es`.
- [es5](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage).
- [ie11](https://github.com/Volox/eslint-plugin-ie11) - Detect unsupported ES6 features in IE11.

### CSS in JS

- [CSS-modules](https://github.com/atfzl/eslint-plugin-css-modules) - Lint undefined or unused rules for css modules.
- [Emotion](https://github.com/emotion-js/emotion/tree/master/packages/eslint-plugin) - ESLint rules for emotion.
- Styled Components
  - [Better Styled Components](https://github.com/tinloof/eslint-plugin-better-styled-components) - Auto fixable ESlint's rules for styled components.
  - [styled-components-a11y](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y) - A11y for Styled Components.
- [vanilla-extract](https://github.com/antebudimir/eslint-plugin-vanilla-extract) - An ESLint plugin for enforcing CSS property ordering in [vanilla-extract CSS](https://github.com/vanilla-extract-css/vanilla-extract) styles.

### Deprecation

- [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used.
- [disable](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments.

### Embedded

- [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags.
- [Markdown](https://github.com/eslint/eslint-plugin-markdown) - Linting for JavaScript inside of Markdown.

### Frameworks

- [Angular](https://github.com/angular-eslint/angular-eslint) - Linting rules for Angular (v2+).
- [AngularJS](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the [John Papa's AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide).
- [Astro](https://github.com/ota-meshi/eslint-plugin-astro) - Plugin for [Astro components](https://docs.astro.build/en/core-concepts/astro-components/).
- [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone.
- [Ember](https://github.com/ember-cli/eslint-plugin-ember) - Linting rules for Ember.
- [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) - Linting rules for hapi.
- [Meteor](https://github.com/meteor/meteor/tree/devel/npm-packages/eslint-plugin-meteor) - Meteor specific linting rules for ESLint.
- React
  - [JSX a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements.
  - [React](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX.
  - [React Hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - Linting rules for React Hooks.
  - [React Native](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules.
  - [React-Redux](https://github.com/DianaSuvorova/eslint-plugin-react-redux) - React-Redux specific linting rules.
  - [React Refresh](https://github.com/ArnaudBarre/eslint-plugin-react-refresh) - Improve HMR experience when using Vite.
- [Solid](https://github.com/joshwilsonvu/eslint-plugin-solid) - Linting rules for Solid and JSX.
- [Svelte](https://github.com/sveltejs/eslint-plugin-svelte) - Linting rules for Svelte v3 Components.
- Vue
  - [VueJS](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS.
  - [VueJS Scoped CSS](https://github.com/future-architect/eslint-plugin-vue-scoped-css) - Plugin for Scoped CSS in VueJS.

### Languages and Environments

- [Babel](https://github.com/babel/babel/tree/main/eslint/babel-eslint-plugin) - Adds replacements for built-in rules to include Babel features.
- [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins.
- Flow
  - [Flow](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules.
  - [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin.
- [HTML](https://github.com/yeonjuan/html-eslint) - ESLint plugin for HTML.
- JSON
  - [JSON](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files.
  - [JSON, package.json](https://github.com/Bkucera/eslint-plugin-json-format) - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
  - [JSON with Comments](https://github.com/ota-meshi/eslint-plugin-jsonc) - ESLint plugin for JSON, JSONC and JSON5.
  - [JSON Schema](https://github.com/ota-meshi/eslint-plugin-json-schema-validator) - Validates data defined in JavaScript, JSON, YAML and TOML using JSON Schema Validator.
- [MDX](https://github.com/mdx-js/eslint-mdx/tree/master/packages/eslint-plugin-mdx) - ESLint Parser/Plugin for MDX.
- [N](https://github.com/eslint-community/eslint-plugin-n) - Additional ESLint's rules for Node.js. Properly maintained fork of no longer maintained `eslint-plugin-node`.
- [SQL](https://github.com/gajus/eslint-plugin-sql) - SQL linting rules for ESLint.
- [TOML](https://github.com/ota-meshi/eslint-plugin-toml) - ESLint plugin for TOML.
- [TypeScript](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin) - Linting rules for TypeScript.
- [YAML](https://github.com/ota-meshi/eslint-plugin-yml) - ESLint plugin for YAML.

### Libraries

- GraphQL
  - [dotansimha/graphql-eslint](https://github.com/dotansimha/graphql-eslint) - Validates, prettifies and checks your GraphQL operations and GraphQL schema for best-practices.
  - [apollostack/eslint-plugin-graphql](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema.
- [TypeGraphQL](https://github.com/borremosch/eslint-plugin-type-graphql) - Linting rules for TypeGraphQL, targeted at finding common mistakes.
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
- [Tailwind CSS](https://github.com/francoismassart/eslint-plugin-tailwindcss) - Linting rules for Tailwind CSS classnames.

### Misc

- [Diff](https://github.com/paleite/eslint-plugin-diff) - Run ESLint on your changed lines only. Also supports CI!
- [Misc](https://github.com/ilyub/eslint-plugin-misc) - Miscellaneous rules including rules for creating custom checks and wrapping (modifying) third-party rules.
- [Notice](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too!
- [Only-Error](https://github.com/davidjbradshaw/eslint-plugin-only-error) - Convert all rules to errors.
- [Only-Warn](https://github.com/bfanger/eslint-plugin-only-warn) - Convert all rules to warnings.
- [PutOut](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout) - an ESLint plugin integrates [putout](https://github.com/coderaiser/putout) linter into ESLint.
- [TypeLint](https://github.com/yarax/eslint-plugin-typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.
- [Woke](https://github.com/amwmedia/eslint-plugin-woke) - Helps catch insensitive words, promoting an inclusive codebase.

### Practices and Specific ES Features

- [array-func](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.
- [arrow functions](https://github.com/getify/eslint-plugin-proper-arrows) - ESLint rules to ensure proper arrow function definitions.
- [boundaries](https://github.com/javierbrea/eslint-plugin-boundaries) - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
- [@eslint-community/eslint-plugin-eslint-comments](https://github.com/eslint-community/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.). Properly maintained fork of no longer maintained `eslint-plugin-eslint-comments`.
- [eslint-plugin-error-cause](https://github.com/Amnish04/eslint-plugin-error-cause) - A plugin to preserve original error context when re-throwing exceptions.
- [eslint-plugin-hexagonal-architecture](https://github.com/CodelyTV/eslint-plugin-hexagonal-architecture) - A plugin that helps you to enforce hexagonal architecture best practices.
- [eslint-plugin-write-good-comments](https://github.com/kantord/eslint-plugin-write-good-comments) - Enforce good writing style in comments.
- [eslint-plugin-exception-handling](https://github.com/Akronae/eslint-plugin-exception-handling) - Lints unhandled functions that might throw errors.
- [fp](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming.
- [functional](https://github.com/jonaskello/eslint-plugin-functional) - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
- [Immutable](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript.
- [import](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names.
- [import-x](https://github.com/un-ts/eslint-plugin-import-x) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names. Lightweight fork of `eslint-plugin-import`, but which breaks backwards compatibility.
- [Math](https://github.com/ota-meshi/eslint-plugin-math) - ESLint plugin related to Math object and Number.
- [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`.
<!-- lint ignore awesome-spell-check -->
- [no-argument-spread](https://github.com/causalhq/eslint-plugin-no-argument-spread) - Lints against expressions like `Math.max(...args)` that can lead to a stack overflow for large arrays.
- [no-comments](https://github.com/wisniewski94/eslint-plugin-no-comments) - Prevents leaking comments into production if bundler is not used and stops developers from commenting out old lines of code.
- [no-constructor-bind](https://github.com/markalfred/eslint-plugin-no-constructor-bind) - Encourages use of class properties by reporting use of `this` with `bind` or setting state in constructors.
- [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
- [no-loops](https://github.com/buildo/eslint-plugin-no-loops) - It's 2019 and you still use loops?
- [no-restricted-syntax](https://github.com/brettz9/eslint-plugin-query) - Show queried syntax's content in messages.
- [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects.
- [Promise](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises.
- [pure](https://github.com/purely-functional/eslint-plugin-pure) - Enforce pure functions (without side effects).
- [ReDoS](https://makenowjust-labs.github.io/recheck/docs/usage/as-eslint-plugin/) - ESLint plugin for finding possible ReDoS vulnerabilities.
- [ReDoSDetector](https://github.com/tjenkinson/eslint-plugin-redos-detector) - ESLint plugin for finding possible ReDoS vulnerabilities.
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
- [pii](https://github.com/shiva-hack/eslint-plugin-pii) - Checks and enforces PII Compliance of the code. i.e. no email address, birth date, IP address or phone number in comments or string literals.
- [Security](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security.
- [xss](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production.

### Style

- [ESLint Stylistic](https://eslint.style/) - [Formatting and stylistic ESLint core rules moved to this project and are maintained by the community.](https://eslint.org/blog/2023/10/deprecating-formatting-rules/)
- [const case](https://www.npmjs.com/package/eslint-plugin-const-case) - Enforce capitalization of constant primitive literals.
- [editorconfig](https://github.com/platinumazure/eslint-plugin-editorconfig) - Derive rules from [`.editorconfig`](https://editorconfig.org/).
- [filenames](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your JavaScript files. No longer maintained and does not work with ESlint 9 at all.
- [Simple import sort](https://github.com/lydell/eslint-plugin-simple-import-sort) - Easy autofixable import sorting.
- [perfectionist sorting](https://github.com/azat-io/eslint-plugin-perfectionist) - Sort objects, imports, TypeScript types, enums, JSX props, etc.
- [split-and-sort-imports](https://github.com/sngn/eslint-plugin-split-and-sort-imports) - Sorts imports and splits 'multiple' imports into single line imports.
- [Switch case](https://github.com/lukeapage/eslint-plugin-switch-case) - Switch-case-specific linting rules for ESLint.
- [padding](https://github.com/mu-io/eslint-plugin-padding) - Allows/disallows padding between statements.
- [paths](https://github.com/vitonsky/eslint-plugin-paths) - Use paths from tsconfig/jsconfig and auto fix relative paths to aliases.
- [@gitbutler/no-relative-imports](https://www.npmjs.com/package/@gitbutler/no-relative-imports) - Use paths from tsconfig and auto fix relative paths to aliases. Observes tsconfig inheritance.

### Testing Tools

- [AVA](https://github.com/avajs/eslint-plugin-ava) - Linting rules for AVA.
- Chai
  - [expect practices](https://github.com/turbo87/eslint-plugin-chai-expect)
  - [with unused expressions](https://github.com/ihordiachenko/eslint-plugin-chai-friendly)
  - [permitted keywords](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords)
  - [with chai-as-promised plugin](https://github.com/fintechstudios/eslint-plugin-chai-as-promised)
  <!-- lint disable double-link -->
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
- [Playwright](https://github.com/playwright-community/eslint-plugin-playwright) - Linting rules for Playwright.
- [QUnit](https://github.com/platinumazure/eslint-plugin-qunit) - Linting rules for QUnit.
- [TestCafe-Community](https://github.com/testcafe-community/eslint-plugin-testcafe-community) - TestCafe linting rules with env globals (fork from [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe)).
- [Testing Library](https://github.com/testing-library/eslint-plugin-testing-library) - Linting rules for Testing Library.

## Parsers

- [babel-eslint-parser](https://github.com/babel/babel/tree/main/eslint/babel-eslint-parser) - Allows you to lint ALL valid Babel code with the fantastic ESLint.
- [TypeScript](https://github.com/typescript-eslint/typescript-eslint) - A TypeScript parser that produces output compatible with ESLint.
- [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules.
- [GraphQL](https://github.com/dotansimha/graphql-eslint) - Parser for the GraphQL AST. Includes parser, plugin, processor (for non-graphql files) and rules.

## Formatters

<!-- ignore is to keep "github" lower-case -->
<!--lint ignore awesome-spell-check-->

- [html](https://github.com/shuoshubao/eslint-formatter-html) - A enhanced ESLint formatter.
- [badger](https://github.com/brettz9/eslint-formatter-badger) - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
- [git-log](https://github.com/JamieMason/eslint-formatter-git-log) - ESLint Formatter featuring Git Author, Date, and Hash.
- [github](https://github.com/hipstersmoothie/eslint-formatter-github) - See ESLint errors and warnings directly in pull requests.
- [gitlab](https://gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
- [mo](https://github.com/fengzilong/eslint-formatter-mo) - Good-lookin' ESLint formatter and also for delightful reading experience.
- [SARIF](https://www.npmjs.com/package/@microsoft/eslint-formatter-sarif) - Generate a results in a SARIF format so it can be imported into tools like GitHub Advanced Security.
- [summary-chart](https://github.com/davidjbradshaw/eslint-formatter-summary-chart) - Format ESLint output into a bar chart.

## Globals

- [confusing-browser-globals](https://github.com/facebook/create-react-app/tree/main/packages/confusing-browser-globals) - A curated list of browser globals that commonly cause confusion and are not recommended to use without an explicit window. qualifier.
- [ES and browser globals](https://github.com/sindresorhus/globals) (originally from ESLint)
- [chai globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
- [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe) - `fixture` & `test` globals for TestCafe.

## Tools

- [es-file-traverse](https://github.com/brettz9/es-file-traverse) - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
- [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config.
- [eslint-index](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files.
- [eslint-interactive](https://github.com/mizdra/eslint-interactive) - The CLI tool to fix huge number of ESLint errors.
- [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer) - Multiplex eslint results and merge results for common files.
- [eslint-nibble](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time.
- [eslint-plugin-rule-adoption](https://github.com/Jugbot/eslint-plugin-rule-adoption) - An eslint plugin for incremental rule adoption, when `--fix` and codemods don't cut it.
- [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule.
- [eslint-watch](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode.
- [codacy-eslint](https://github.com/codacy/codacy-eslint) - Docker used at [Codacy](https://www.codacy.com) to run ESLint.
- [esprint](https://github.com/pinterest/esprint) - Run ESLint across multiple threads.
- [generator-eslint](https://github.com/eslint/generator-eslint) - Generate ESLint
  plugin and rules with [Yeoman](http://yeoman.io/).
- [editor-info](https://github.com/fisker/editor-info) - Detect whether one is within an editor/IDE and which type, allowing one to tweak ESLint configuration accordingly.
- [eslint-dashboard](https://github.com/fengzilong/eslint-dashboard) - Interactive ESLint workflow that lives in your terminal.
- [eslint-remote-tester](https://github.com/AriPerkkio/eslint-remote-tester) - CLI tool for testing given ESlint rules against multiple repositories at once.

## Developing for ESLint

- [eslint-doc-generator](https://github.com/bmish/eslint-doc-generator) - Generate documentation for your ESLint plugin including a rules table for your readme and header for your rule docs.
- [eslint-docgen](https://github.com/wikimedia/eslint-docgen) - Automatically generate ESLint plugin documentation from rule metadata and test cases.

## Tutorials

- [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
- [Lint Like It's 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.
- [Dear Old ESLint](https://adropincalm.com/blog/dear-old-eslint/) - Quick intro article on ESLint.

## Installation and Setup

- [Lintier](https://github.com/josh-stillman/lintier) - CLI to quickly scaffold an ESLint & Prettier setup in a TypeScript project.

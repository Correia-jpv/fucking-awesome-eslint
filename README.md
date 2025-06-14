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

- <b><code>146840⭐</code></b> <b><code>&nbsp;26754🍴</code></b> [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb)) - Shareable config for <b><code>146840⭐</code></b> <b><code>&nbsp;26754🍴</code></b> [Airbnb's style guide](https://github.com/airbnb/javascript)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Airbnb-babel](https://github.com/davidjbradshaw/eslint-config-airbnb-babel)) - Airbnb's ESLint config with Babel Support.
- <b><code>&nbsp;&nbsp;2649⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;312🍴</code></b> [Alloy](https://github.com/AlloyTeam/eslint-config-alloy)) - Progressive ESLint config for your React/Vue/TypeScript projects.
- <b><code>&nbsp;26008⭐</code></b> <b><code>&nbsp;&nbsp;4735🍴</code></b> [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint)) - Contains the ESLint configuration used for projects maintained by the ESLint team.
- 🌎 [Facebook](www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Feedzai](https://github.com/feedzai/eslint-config-feedzai)) - Feedzai's shareable config for JavaScript/React projects.
- <b><code>&nbsp;&nbsp;&nbsp;478⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Shopify](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md)) - Shareable config for <b><code>&nbsp;&nbsp;&nbsp;257⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [Shopify's style guide](https://github.com/Shopify/javascript)).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21🍴</code></b> [Wikimedia](https://github.com/wikimedia/eslint-config-wikimedia)) - Shareable config for 🌎 [Wikimedia's style guide](www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by 🌎 [MediaWiki](www.mediawiki.org/).

### Other Prominent Configs (100 stars or so)

- <b><code>&nbsp;&nbsp;&nbsp;403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [Auto](https://github.com/davidjbradshaw/eslint-config-auto)) - Automatically configure ESLint based on your project's dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;614⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [Canonical](https://github.com/gajus/eslint-config-canonical)) - Shareable config for <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Canonical style guide](https://github.com/gajus/canonical)).
<!-- lint disable double-link -->
- <b><code>&nbsp;&nbsp;2642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;558🍴</code></b> [Standard](https://github.com/feross/eslint-config-standard)) - Shareable config for JavaScript <b><code>&nbsp;29321⭐</code></b> <b><code>&nbsp;&nbsp;2319🍴</code></b> [Standard Style](https://github.com/feross/standard)).
- <b><code>&nbsp;&nbsp;&nbsp;275⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [XO](https://github.com/xojs/eslint-config-xo)) - Shareable config for <b><code>&nbsp;&nbsp;7787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [XO](https://github.com/xojs/xo)).
- <b><code>&nbsp;&nbsp;5290⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;519🍴</code></b> [Antfu Eslint Config](https://github.com/antfu/eslint-config)) - Anthony's ESLint config preset.

### Other Configs

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Adjunct](https://github.com/davidjbradshaw/eslint-config-adjunct)) - A reasonable collection of plugins to use alongside your main ESLint configuration.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Ash-Nazg](https://github.com/brettz9/eslint-config-ash-nazg)) - One config to rule them all!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Cecilia](https://github.com/SandroMiguel/eslint-config-cecilia)) - ESLint configuration for awesome projects.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [clean-typescript](https://github.com/cunarist/eslint-config-clean-typescript)) - Enforce classic JavaScript featuress in TypeScript codebase by banning excessive keywords.
- <b><code>&nbsp;&nbsp;&nbsp;443⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [Hardcore](https://github.com/EvgenyOrekhov/eslint-config-hardcore)) - The most strict (but practical) ESLint config out there.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Problems](https://github.com/RyanZim/eslint-config-problems)) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Supermind](https://github.com/supermind/eslint-config-supermind)) - Shareable config for Supermind style.
- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Sheriff](https://github.com/AndreaPontrandolfo/sheriff)) - Comprehensive and highly opinionated Eslint configuration. Typescript oriented.

## Preconfigured Configs with ESLint Set up

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Node.js Standard Style](https://github.com/geek/node-style)) - Node.js core config.
- <b><code>&nbsp;&nbsp;5707⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;256🍴</code></b> [eslint-config-prettier](https://github.com/prettier/eslint-config-prettier)) - Prettier config for ESlint maintained by Prettier team.
- <b><code>&nbsp;29321⭐</code></b> <b><code>&nbsp;&nbsp;2319🍴</code></b> [Standard](https://github.com/feross/standard)) - JavaScript Standard Style.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Superlint](https://github.com/supermind/superlint)) - JavaScript Supermind Style.
- <b><code>&nbsp;&nbsp;7787⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;294🍴</code></b> [XO](https://github.com/sindresorhus/xo)) - JavaScript happiness style linter ❤️.

## Plugins

### Code Quality

- <b><code>&nbsp;&nbsp;&nbsp;402⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [depend](https://github.com/es-tooling/eslint-plugin-depend)) - Helps detect dependency tree bloat and redundant polyfills.
- <b><code>&nbsp;&nbsp;&nbsp;314⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [GitHub](https://github.com/github/eslint-plugin-github)) - Misc. rules from GitHub.
- <b><code>&nbsp;&nbsp;1111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [SonarJS](https://github.com/SonarSource/SonarJS/blob/master/packages/jsts/src/rules/README.md)) - Rules detecting bugs and suspicious patterns.
- <b><code>&nbsp;&nbsp;4539⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;404🍴</code></b> [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)) - Various awesome ESLint rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [@mysticatea/eslint-plugin](https://github.com/mysticatea/eslint-plugin)) - Misc. rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [@brettz9/eslint-plugin](https://github.com/brettz9/eslint-plugin)) - Misc. rules. of `@mysticatea` without the personal config.
- <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [De Morgan](https://github.com/azat-io/eslint-plugin-de-morgan)) - Transforms logical expressions in code to make them easier to understand.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [eslint-plugin-code-complete](https://github.com/aryelu/eslint-plugin-code-complete)) - A custom ESLint plugin that enforces principles of clean, maintainable software design — inspired by Code Complete.



### Compatibility

- <b><code>&nbsp;&nbsp;3126⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Compat](https://github.com/amilajack/eslint-plugin-compat)) - Lint browser compatibility of APIs used ([caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;69⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [ecmascript-compat](https://github.com/robatwilliams/es-compat)) - Disable ECMAScript language features not supported by your browserslist targets.
- <b><code>&nbsp;&nbsp;&nbsp;137⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [es-x](https://github.com/eslint-community/eslint-plugin-es-x)) - Disable specific ECMAScript language versions or individual features. Properly maintained fork of no longer maintained `eslint-plugin-es`.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [es5](https://github.com/nkt/eslint-plugin-es5)) - ESLint plugin for ES5 users (forbid ES2015+ usage).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ie11](https://github.com/Volox/eslint-plugin-ie11)) - Detect unsupported ES6 features in IE11.

### CSS in JS

- <b><code>&nbsp;&nbsp;&nbsp;153⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [CSS-modules](https://github.com/atfzl/eslint-plugin-css-modules)) - Lint undefined or unused rules for css modules.
- <b><code>&nbsp;17784⭐</code></b> <b><code>&nbsp;&nbsp;1129🍴</code></b> [Emotion](https://github.com/emotion-js/emotion/tree/master/packages/eslint-plugin)) - ESLint rules for emotion.
- Styled Components
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Better Styled Components](https://github.com/tinloof/eslint-plugin-better-styled-components)) - Auto fixable ESlint's rules for styled components.
  - <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [styled-components-a11y](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y)) - A11y for Styled Components.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [vanilla-extract](https://github.com/antebudimir/eslint-plugin-vanilla-extract)) - An ESLint plugin for enforcing CSS property ordering in <b><code>&nbsp;&nbsp;9943⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;318🍴</code></b> [vanilla-extract CSS](https://github.com/vanilla-extract-css/vanilla-extract)) styles.

### Deprecation

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;82⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate)) - Mark functions or modules as deprecated and get lint messages when they are used.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [disable](https://github.com/mradionov/eslint-plugin-disable)) - Disable specified plugins using file path patterns and inline comments.

### Embedded

- <b><code>&nbsp;&nbsp;&nbsp;442⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html)) - Linting for JavaScript inside of HTML `<script>` tags.
- <b><code>&nbsp;&nbsp;&nbsp;468⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72🍴</code></b> [Markdown](https://github.com/eslint/eslint-plugin-markdown)) - Linting for JavaScript inside of Markdown.

### Frameworks

- <b><code>&nbsp;&nbsp;1725⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;242🍴</code></b> [Angular](https://github.com/angular-eslint/angular-eslint)) - Linting rules for Angular (v2+).
- <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;130🍴</code></b> [AngularJS](https://github.com/Gillespie59/eslint-plugin-angular)) - Linting rules to adhere to the <b><code>&nbsp;23806⭐</code></b> <b><code>&nbsp;&nbsp;4125🍴</code></b> [John Papa's AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide)).
- <b><code>&nbsp;&nbsp;&nbsp;370⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Astro](https://github.com/ota-meshi/eslint-plugin-astro)) - Plugin for 🌎 [Astro components](docs.astro.build/en/core-concepts/astro-components/).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;95⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone)) - Linting rules for Backbone.
- <b><code>&nbsp;&nbsp;&nbsp;262⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;205🍴</code></b> [Ember](https://github.com/ember-cli/eslint-plugin-ember)) - Linting rules for Ember.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi)) - Linting rules for hapi.
- <b><code>&nbsp;44653⭐</code></b> <b><code>&nbsp;&nbsp;5210🍴</code></b> [Meteor](https://github.com/meteor/meteor/tree/devel/npm-packages/eslint-plugin-meteor)) - Meteor specific linting rules for ESLint.
- React
  - <b><code>&nbsp;&nbsp;3501⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;636🍴</code></b> [JSX a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)) - Accessibility rules on JSX elements.
  - <b><code>&nbsp;&nbsp;9171⭐</code></b> <b><code>&nbsp;&nbsp;2762🍴</code></b> [React](https://github.com/yannickcr/eslint-plugin-react)) - Linting rules for React and JSX.
  - <b><code>236337⭐</code></b> <b><code>&nbsp;48741🍴</code></b> [React Hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks)) - Linting rules for React Hooks.
  - <b><code>&nbsp;&nbsp;&nbsp;742⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;131🍴</code></b> [React Native](https://github.com/Intellicode/eslint-plugin-react-native)) - React Native specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [React-Redux](https://github.com/DianaSuvorova/eslint-plugin-react-redux)) - React-Redux specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;283⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [React Refresh](https://github.com/ArnaudBarre/eslint-plugin-react-refresh)) - Improve HMR experience when using Vite.
- <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [Solid](https://github.com/joshwilsonvu/eslint-plugin-solid)) - Linting rules for Solid and JSX.
- <b><code>&nbsp;&nbsp;&nbsp;339⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Svelte](https://github.com/sveltejs/eslint-plugin-svelte)) - Linting rules for Svelte v3 Components.
- Vue
  - <b><code>&nbsp;&nbsp;4540⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;680🍴</code></b> [VueJS](https://github.com/vuejs/eslint-plugin-vue)) - Plugin for VueJS.
  - <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [VueJS Scoped CSS](https://github.com/future-architect/eslint-plugin-vue-scoped-css)) - Plugin for Scoped CSS in VueJS.

### Languages and Environments

- <b><code>&nbsp;43614⭐</code></b> <b><code>&nbsp;&nbsp;5720🍴</code></b> [Babel](https://github.com/babel/babel/tree/main/eslint/babel-eslint-plugin)) - Adds replacements for built-in rules to include Babel features.
- <b><code>&nbsp;&nbsp;&nbsp;210⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin)) - An ESLint plugin for linting ESLint plugins.
- Flow
  - <b><code>&nbsp;&nbsp;1072⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;154🍴</code></b> [Flow](https://github.com/gajus/eslint-plugin-flowtype)) - Flow type linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;403⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors)) - Run Flow as an ESLint plugin.
- <b><code>&nbsp;&nbsp;&nbsp;227⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45🍴</code></b> [HTML](https://github.com/yeonjuan/html-eslint)) - ESLint plugin for HTML.
- JSON
  - <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [JSON](https://github.com/azeemba/eslint-plugin-json)) - Lint your JSON files.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [JSON, package.json](https://github.com/Bkucera/eslint-plugin-json-format)) - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
  - <b><code>&nbsp;&nbsp;&nbsp;216⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [JSON with Comments](https://github.com/ota-meshi/eslint-plugin-jsonc)) - ESLint plugin for JSON, JSONC and JSON5.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [JSON Schema](https://github.com/ota-meshi/eslint-plugin-json-schema-validator)) - Validates data defined in JavaScript, JSON, YAML and TOML using JSON Schema Validator.
- <b><code>&nbsp;&nbsp;&nbsp;284⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34🍴</code></b> [MDX](https://github.com/mdx-js/eslint-mdx/tree/master/packages/eslint-plugin-mdx)) - ESLint Parser/Plugin for MDX.
- <b><code>&nbsp;&nbsp;&nbsp;288⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [N](https://github.com/eslint-community/eslint-plugin-n)) - Additional ESLint's rules for Node.js. Properly maintained fork of no longer maintained `eslint-plugin-node`.
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [SQL](https://github.com/gajus/eslint-plugin-sql)) - SQL linting rules for ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [TOML](https://github.com/ota-meshi/eslint-plugin-toml)) - ESLint plugin for TOML.
- <b><code>&nbsp;15773⭐</code></b> <b><code>&nbsp;&nbsp;2793🍴</code></b> [TypeScript](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin)) - Linting rules for TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;143⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [YAML](https://github.com/ota-meshi/eslint-plugin-yml)) - ESLint plugin for YAML.

### Libraries

- GraphQL
  - <b><code>&nbsp;&nbsp;&nbsp;827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [dotansimha/graphql-eslint](https://github.com/dotansimha/graphql-eslint)) - Validates, prettifies and checks your GraphQL operations and GraphQL schema for best-practices.
  - <b><code>&nbsp;&nbsp;1217⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [apollostack/eslint-plugin-graphql](https://github.com/apollostack/eslint-plugin-graphql)) - Check your GraphQL query strings against a schema.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [TypeGraphQL](https://github.com/borremosch/eslint-plugin-type-graphql)) - Linting rules for TypeGraphQL, targeted at finding common mistakes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [jQuery](https://github.com/wikimedia/eslint-plugin-no-jquery)) - Linting rules for jQuery, including versioned configs for deprecated features.
- <b><code>&nbsp;&nbsp;1156⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;166🍴</code></b> [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc)) - Linting rules for JSDoc comments (including the JavaScript within `@example`).
- Lodash
  - <b><code>&nbsp;&nbsp;&nbsp;279⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65🍴</code></b> [Lodash](https://github.com/wix/eslint-plugin-lodash)) - Lodash specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;151⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp)) - Lodash/fp specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Lodash template](https://github.com/ota-meshi/eslint-plugin-lodash-template)) - Plugin for Lodash template/Underscore template.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Microtemplates](https://github.com/platinumazure/eslint-plugin-microtemplates)) (Used in Lodash and Underscore.js)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb)) - Mongodb native Node.js driver linting rules.
- <b><code>&nbsp;&nbsp;&nbsp;117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [Ramda](https://github.com/ramda/eslint-plugin-ramda)) - Ramda specific linting rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [RequireJS](https://github.com/cvisco/eslint-plugin-requirejs)) - Linting rules for RequireJS.
- <b><code>&nbsp;&nbsp;1887⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [Tailwind CSS](https://github.com/francoismassart/eslint-plugin-tailwindcss)) - Linting rules for Tailwind CSS classnames.

### Misc

- <b><code>&nbsp;&nbsp;&nbsp;196⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [Diff](https://github.com/paleite/eslint-plugin-diff)) - Run ESLint on your changed lines only. Also supports CI!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Misc](https://github.com/ilyub/eslint-plugin-misc)) - Miscellaneous rules including rules for creating custom checks and wrapping (modifying) third-party rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Notice](https://github.com/nickdeis/eslint-plugin-notice)) - An eslint rule that checks the top of files and fixes them too!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Only-Error](https://github.com/davidjbradshaw/eslint-plugin-only-error)) - Convert all rules to errors.
- <b><code>&nbsp;&nbsp;&nbsp;175⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Only-Warn](https://github.com/bfanger/eslint-plugin-only-warn)) - Convert all rules to warnings.
- <b><code>&nbsp;&nbsp;&nbsp;754⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [PutOut](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout)) - an ESLint plugin integrates <b><code>&nbsp;&nbsp;&nbsp;754⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [putout](https://github.com/coderaiser/putout)) linter into ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [TypeLint](https://github.com/yarax/eslint-plugin-typelint)) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Woke](https://github.com/amwmedia/eslint-plugin-woke)) - Helps catch insensitive words, promoting an inclusive codebase.

### Practices and Specific ES Features

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [array-func](https://github.com/freaktechnik/eslint-plugin-array-func)) - Avoid redundancy when using es2015 array methods and functions.
- <b><code>&nbsp;&nbsp;&nbsp;308⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [arrow functions](https://github.com/getify/eslint-plugin-proper-arrows)) - ESLint rules to ensure proper arrow function definitions.
- <b><code>&nbsp;&nbsp;&nbsp;657⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [boundaries](https://github.com/javierbrea/eslint-plugin-boundaries)) - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [@eslint-community/eslint-plugin-eslint-comments](https://github.com/eslint-community/eslint-plugin-eslint-comments)) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.). Properly maintained fork of no longer maintained `eslint-plugin-eslint-comments`.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [eslint-plugin-error-cause](https://github.com/Amnish04/eslint-plugin-error-cause)) - A plugin to preserve original error context when re-throwing exceptions.
- <b><code>&nbsp;&nbsp;&nbsp;305⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [eslint-plugin-hexagonal-architecture](https://github.com/CodelyTV/eslint-plugin-hexagonal-architecture)) - A plugin that helps you to enforce hexagonal architecture best practices.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [eslint-plugin-write-good-comments](https://github.com/kantord/eslint-plugin-write-good-comments)) - Enforce good writing style in comments.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [eslint-plugin-exception-handling](https://github.com/Akronae/eslint-plugin-exception-handling)) - Lints unhandled functions that might throw errors.
- <b><code>&nbsp;&nbsp;&nbsp;970⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [fp](https://github.com/jfmengels/eslint-plugin-fp)) - ESLint rules for functional programming.
- <b><code>&nbsp;&nbsp;&nbsp;920⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [functional](https://github.com/jonaskello/eslint-plugin-functional)) - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;910⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [Immutable](https://github.com/jhusain/eslint-plugin-immutable)) - Disable all mutation in JavaScript.
- <b><code>&nbsp;&nbsp;5746⭐</code></b> <b><code>&nbsp;&nbsp;1546🍴</code></b> [import](https://github.com/benmosher/eslint-plugin-import)) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names.
- <b><code>&nbsp;&nbsp;&nbsp;556⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46🍴</code></b> [import-x](https://github.com/un-ts/eslint-plugin-import-x)) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names. Lightweight fork of `eslint-plugin-import`, but which breaks backwards compatibility.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Math](https://github.com/ota-meshi/eslint-plugin-math)) - ESLint plugin related to Math object and Number.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error)) - Require errors to be thrown using `new`.
<!-- lint ignore awesome-spell-check -->
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [no-argument-spread](https://github.com/causalhq/eslint-plugin-no-argument-spread)) - Lints against expressions like `Math.max(...args)` that can lead to a stack overflow for large arrays.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [no-comments](https://github.com/wisniewski94/eslint-plugin-no-comments)) - Prevents leaking comments into production if bundler is not used and stops developers from commenting out old lines of code.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [no-constructor-bind](https://github.com/markalfred/eslint-plugin-no-constructor-bind)) - Encourages use of class properties by reporting use of `this` with `bind` or setting state in constructors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name)) - Custom rule for ESLint that checks for inferred method names within object literals.
- <b><code>&nbsp;&nbsp;&nbsp;130⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [no-loops](https://github.com/buildo/eslint-plugin-no-loops)) - It's 2019 and you still use loops?
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [no-restricted-syntax](https://github.com/brettz9/eslint-plugin-query)) - Show queried syntax's content in messages.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native)) - Prevent using extended native objects.
- <b><code>&nbsp;&nbsp;&nbsp;971⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93🍴</code></b> [Promise](https://github.com/xjamundx/eslint-plugin-promise)) - Best practices when working with promises.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [pure](https://github.com/purely-functional/eslint-plugin-pure)) - Enforce pure functions (without side effects).
- 🌎 [ReDoS](makenowjust-labs.github.io/recheck/docs/usage/as-eslint-plugin/) - ESLint plugin for finding possible ReDoS vulnerabilities.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [ReDoSDetector](https://github.com/tjenkinson/eslint-plugin-redos-detector)) - ESLint plugin for finding possible ReDoS vulnerabilities.
- <b><code>&nbsp;&nbsp;&nbsp;726⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [RegExp](https://github.com/ota-meshi/eslint-plugin-regexp)) - ESLint plugin for finding regexp mistakes and style guide violations.
- <b><code>&nbsp;&nbsp;&nbsp;100⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [sort-keys-fix](https://github.com/leo-buneev/eslint-plugin-sort-keys-fix)) - Adds fixer for ESLint `sort-keys` rule.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [this](https://github.com/matijs/eslint-plugin-this)) - Write pure functions, don't allow `this`.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [toplevel](https://github.com/HKalbasi/eslint-plugin-toplevel)) - An eslint plugin for disallow side effect at module toplevel.

### Performance

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [DOM](https://github.com/amilajack/eslint-plugin-dom))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;76⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [Optimize Regex](https://github.com/BrainMaestro/eslint-plugin-optimize-regex)) - Optimize regex literals.
- Perf-Standard <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [plugin](https://github.com/Raynos/eslint-plugin-perf-standard)) and <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Config](https://github.com/Raynos/eslint-config-perf-standard))

### Security

- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [no-secrets](https://github.com/nickdeis/eslint-plugin-no-secrets)) - An eslint plugin that detects potential secrets/credentials.
- <b><code>&nbsp;&nbsp;&nbsp;238⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [no-unsanitized](https://github.com/mozilla/eslint-plugin-no-unsanitized)) - Checks for `innerHTML`, `outerHTML`, etc.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [pii](https://github.com/shiva-hack/eslint-plugin-pii)) - Checks and enforces PII Compliance of the code. i.e. no email address, birth date, IP address or phone number in comments or string literals.
- <b><code>&nbsp;&nbsp;2277⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;105🍴</code></b> [Security](https://github.com/nodesecurity/eslint-plugin-security)) - ESLint rules for Node Security.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [xss](https://github.com/Rantanen/eslint-plugin-xss)) - Tries to detect XSS issues in codebase before they end up in production.

### Style

- 🌎 [ESLint Stylistic](eslint.style/) - 🌎 [Formatting and stylistic ESLint core rules moved to this project and are maintained by the community.](eslint.org/blog/2023/10/deprecating-formatting-rules/)
- 🌎 [const case](www.npmjs.com/package/eslint-plugin-const-case) - Enforce capitalization of constant primitive literals.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [editorconfig](https://github.com/platinumazure/eslint-plugin-editorconfig)) - Derive rules from 🌎 [`.editorconfig`](editorconfig.org/).
- <b><code>&nbsp;&nbsp;&nbsp;323⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35🍴</code></b> [filenames](https://github.com/selaux/eslint-plugin-filenames)) - Ensure consistent filenames for your JavaScript files. No longer maintained and does not work with ESlint 9 at all.
- <b><code>&nbsp;&nbsp;2280⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;73🍴</code></b> [Simple import sort](https://github.com/lydell/eslint-plugin-simple-import-sort)) - Easy autofixable import sorting.
- <b><code>&nbsp;&nbsp;2581⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [perfectionist sorting](https://github.com/azat-io/eslint-plugin-perfectionist)) - Sort objects, imports, TypeScript types, enums, JSX props, etc.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [split-and-sort-imports](https://github.com/sngn/eslint-plugin-split-and-sort-imports)) - Sorts imports and splits 'multiple' imports into single line imports.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Switch case](https://github.com/lukeapage/eslint-plugin-switch-case)) - Switch-case-specific linting rules for ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [padding](https://github.com/mu-io/eslint-plugin-padding)) - Allows/disallows padding between statements.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;79⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [paths](https://github.com/vitonsky/eslint-plugin-paths)) - Use paths from tsconfig/jsconfig and auto fix relative paths to aliases.
- 🌎 [@gitbutler/no-relative-imports](www.npmjs.com/package/@gitbutler/no-relative-imports) - Use paths from tsconfig and auto fix relative paths to aliases. Observes tsconfig inheritance.

### Testing Tools

- <b><code>&nbsp;&nbsp;&nbsp;229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [AVA](https://github.com/avajs/eslint-plugin-ava)) - Linting rules for AVA.
- Chai
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [expect practices](https://github.com/turbo87/eslint-plugin-chai-expect))
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [with unused expressions](https://github.com/ihordiachenko/eslint-plugin-chai-friendly))
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [permitted keywords](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords))
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [with chai-as-promised plugin](https://github.com/fintechstudios/eslint-plugin-chai-as-promised))
  <!-- lint disable double-link -->
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [Cucumber](https://github.com/darrinholst/eslint-plugin-cucumber)) - Linting rules for Cucumber.
- <b><code>&nbsp;&nbsp;&nbsp;717⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Cypress](https://github.com/cypress-io/eslint-plugin-cypress)) - Linting rules for Cypress.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;99⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57🍴</code></b> [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine)) - Linting rules for Jasmine.
- Jest
  - <b><code>&nbsp;&nbsp;1157⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;241🍴</code></b> [Enforcing practices](https://github.com/jest-community/eslint-plugin-jest)) - Linting rules for Jest.
  - <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Enforcing consistent formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting)) - Formatting rules for Jest.
  - 🌎 [Jest-async](www.npmjs.com/package/eslint-plugin-jest-async) - Async linting rule for Jest.
  - <b><code>&nbsp;&nbsp;&nbsp;368⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Jest-DOM](https://github.com/testing-library/eslint-plugin-jest-dom)) - Linting rules for Jest-DOM.
- Mocha
  - <b><code>&nbsp;&nbsp;&nbsp;286⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Enforcing practices](https://github.com/lo1tuma/eslint-plugin-mocha)) - Linting rules for Mocha.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Enforcing manageability](https://github.com/onechiporenko/eslint-plugin-mocha-cleanup/))
- <b><code>&nbsp;&nbsp;&nbsp;321⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Playwright](https://github.com/playwright-community/eslint-plugin-playwright)) - Linting rules for Playwright.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [QUnit](https://github.com/platinumazure/eslint-plugin-qunit)) - Linting rules for QUnit.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [TestCafe-Community](https://github.com/testcafe-community/eslint-plugin-testcafe-community)) - TestCafe linting rules with env globals (fork from <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe))).
- <b><code>&nbsp;&nbsp;1014⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [Testing Library](https://github.com/testing-library/eslint-plugin-testing-library)) - Linting rules for Testing Library.

## Parsers

- <b><code>&nbsp;43614⭐</code></b> <b><code>&nbsp;&nbsp;5720🍴</code></b> [babel-eslint-parser](https://github.com/babel/babel/tree/main/eslint/babel-eslint-parser)) - Allows you to lint ALL valid Babel code with the fantastic ESLint.
- <b><code>&nbsp;15773⭐</code></b> <b><code>&nbsp;&nbsp;2793🍴</code></b> [TypeScript](https://github.com/typescript-eslint/typescript-eslint)) - A TypeScript parser that produces output compatible with ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku)) - BrightScript plugin for Roku development. Includes Parser and Rules.
- <b><code>&nbsp;&nbsp;&nbsp;827⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;109🍴</code></b> [GraphQL](https://github.com/dotansimha/graphql-eslint)) - Parser for the GraphQL AST. Includes parser, plugin, processor (for non-graphql files) and rules.

## Formatters

<!-- ignore is to keep "github" lower-case -->
<!--lint ignore awesome-spell-check-->

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [html](https://github.com/shuoshubao/eslint-formatter-html)) - A enhanced ESLint formatter.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [badger](https://github.com/brettz9/eslint-formatter-badger)) - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [git-log](https://github.com/JamieMason/eslint-formatter-git-log)) - ESLint Formatter featuring Git Author, Date, and Hash.
- <b><code>&nbsp;&nbsp;&nbsp;107⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [github](https://github.com/hipstersmoothie/eslint-formatter-github)) - See ESLint errors and warnings directly in pull requests.
- 🌎 [gitlab](gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
- <b><code>&nbsp;&nbsp;&nbsp;131⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [mo](https://github.com/fengzilong/eslint-formatter-mo)) - Good-lookin' ESLint formatter and also for delightful reading experience.
- 🌎 [SARIF](www.npmjs.com/package/@microsoft/eslint-formatter-sarif) - Generate a results in a SARIF format so it can be imported into tools like GitHub Advanced Security.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [summary-chart](https://github.com/davidjbradshaw/eslint-formatter-summary-chart)) - Format ESLint output into a bar chart.

## Globals

- <b><code>103295⭐</code></b> <b><code>&nbsp;27022🍴</code></b> [confusing-browser-globals](https://github.com/facebook/create-react-app/tree/main/packages/confusing-browser-globals)) - A curated list of browser globals that commonly cause confusion and are not recommended to use without an explicit window. qualifier.
- <b><code>&nbsp;&nbsp;&nbsp;483⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [ES and browser globals](https://github.com/sindresorhus/globals)) (originally from ESLint)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [chai globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd))
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe)) - `fixture` & `test` globals for TestCafe.

## Tools

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [es-file-traverse](https://github.com/brettz9/es-file-traverse)) - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;213⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38🍴</code></b> [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules)) - Find built-in ESLint rules you don't have in your custom config.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [eslint-index](https://github.com/wagerfield/eslint-index)) - CLI for finding and managing rules in ESLint config files.
- <b><code>&nbsp;&nbsp;&nbsp;417⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [eslint-interactive](https://github.com/mizdra/eslint-interactive)) - The CLI tool to fix huge number of ESLint errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer)) - Multiplex eslint results and merge results for common files.
- <b><code>&nbsp;&nbsp;&nbsp;841⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [eslint-nibble](https://github.com/IanVS/eslint-nibble)) - Ease into ESLint, by fixing one rule at a time.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [eslint-plugin-rule-adoption](https://github.com/Jugbot/eslint-plugin-rule-adoption)) - An eslint plugin for incremental rule adoption, when `--fix` and codemods don't cut it.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31🍴</code></b> [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation)) - Find the url for the documentation of an ESLint rule.
- <b><code>&nbsp;&nbsp;&nbsp;197⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [eslint-watch](https://github.com/rizowski/eslint-watch)) - Run ESLint with watch mode.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20🍴</code></b> [codacy-eslint](https://github.com/codacy/codacy-eslint)) - Docker used at 🌎 [Codacy](www.codacy.com) to run ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54🍴</code></b> [esprint](https://github.com/pinterest/esprint)) - Run ESLint across multiple threads.
- <b><code>&nbsp;&nbsp;&nbsp;237⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [generator-eslint](https://github.com/eslint/generator-eslint)) - Generate ESLint
  plugin and rules with [Yeoman](http://yeoman.io/).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [editor-info](https://github.com/fisker/editor-info)) - Detect whether one is within an editor/IDE and which type, allowing one to tweak ESLint configuration accordingly.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [eslint-dashboard](https://github.com/fengzilong/eslint-dashboard)) - Interactive ESLint workflow that lives in your terminal.
- <b><code>&nbsp;&nbsp;&nbsp;133⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [eslint-remote-tester](https://github.com/AriPerkkio/eslint-remote-tester)) - CLI tool for testing given ESlint rules against multiple repositories at once.

## Developing for ESLint

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [eslint-doc-generator](https://github.com/bmish/eslint-doc-generator)) - Generate documentation for your ESLint plugin including a rules table for your readme and header for your rule docs.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [eslint-docgen](https://github.com/wikimedia/eslint-docgen)) - Automatically generate ESLint plugin documentation from rule metadata and test cases.

## Tutorials

- 🌎 [Creating an ESLint Plugin](medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
- 🌎 [Lint Like It's 2015](medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
- [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.
- 🌎 [Dear Old ESLint](adropincalm.com/blog/dear-old-eslint/) - Quick intro article on ESLint.

## Installation and Setup

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Lintier](https://github.com/josh-stillman/lintier)) - CLI to quickly scaffold an ESLint & Prettier setup in a TypeScript project.

## Source
<b><code>&nbsp;&nbsp;4566⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;239🍴</code></b> [dustinspecker/awesome-eslint](https://github.com/dustinspecker/awesome-eslint))
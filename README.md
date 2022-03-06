# Awesome ESLint [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
 🌎 [<img src="https://eslint.org/assets/img/logo.svg" width="160" align="right" alt="eslint">](http://eslint.org)

> A list of awesome ESLint configs, plugins, etc.

If you want to contribute, please read the 🌎 [contribution guidelines](contributing.md).

<!--lint disable double-link-->

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

- <b><code>120470⭐</code></b> <b><code>&nbsp;22980🍴</code></b> [Airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) - Shareable config for <b><code>120470⭐</code></b> <b><code>&nbsp;22980🍴</code></b> [Airbnb's style guide](https://github.com/airbnb/javascript).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Airbnb-babel](https://github.com/davidjbradshaw/eslint-config-airbnb-babel) - Airbnb's ESLint config with Babel Support.
- <b><code>&nbsp;&nbsp;&nbsp;719⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Airbnb-typescript](https://github.com/iamturns/eslint-config-airbnb-typescript) - Airbnb's ESLint config with TypeScript support.
- <b><code>&nbsp;&nbsp;2273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;313🍴</code></b> [Alloy](https://github.com/AlloyTeam/eslint-config-alloy) - Progressive ESLint config for your React/Vue/TypeScript projects.
- <b><code>&nbsp;20129⭐</code></b> <b><code>&nbsp;&nbsp;3603🍴</code></b> [ESLint](https://github.com/eslint/eslint/tree/master/packages/eslint-config-eslint) - Contains the ESLint configuration used for projects maintained by the ESLint team.
- 🌎 [Facebook](https://www.npmjs.com/package/eslint-config-fbjs) - Sharable config for Facebook's style guide.
- <b><code>&nbsp;&nbsp;1589⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;150🍴</code></b> [Google](https://github.com/google/eslint-config-google) - Shareable config for the 🌎 [Google style](http://google.github.io/styleguide/javascriptguide.xml).
- <b><code>&nbsp;93745⭐</code></b> <b><code>&nbsp;24032🍴</code></b> [React App](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app) - Sharable config for 🌎 [React](https://reactjs.org) projects.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Shopify](https://github.com/Shopify/web-foundation/blob/main/packages/eslint-plugin/README.md) - Shareable config for <b><code>&nbsp;&nbsp;&nbsp;234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Shopify's style guide](https://github.com/Shopify/javascript).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Wikimedia](https://github.com/wikimedia/eslint-config-wikimedia) - Shareable config for 🌎 [Wikimedia's style guide](https://www.mediawiki.org/wiki/Manual:Coding_conventions/JavaScript), used by 🌎 [MediaWiki](https://www.mediawiki.org/).

### Other Prominent Configs (100 stars or so)

- <b><code>&nbsp;&nbsp;&nbsp;341⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Auto](https://github.com/davidjbradshaw/eslint-config-auto) - Automatically configure ESLint based on your project's dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;291⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14🍴</code></b> [Canonical](https://github.com/gajus/eslint-config-canonical) - Shareable config for <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Canonical style guide](https://github.com/gajus/canonical).
- <b><code>&nbsp;&nbsp;2269⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;558🍴</code></b> [Standard](https://github.com/feross/eslint-config-standard) - Shareable config for JavaScript <b><code>&nbsp;26731⭐</code></b> <b><code>&nbsp;&nbsp;2180🍴</code></b> [Standard Style](https://github.com/feross/standard).
- <b><code>&nbsp;&nbsp;&nbsp;219⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43🍴</code></b> [XO](https://github.com/xojs/eslint-config-xo) - Shareable config for <b><code>&nbsp;&nbsp;6459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [XO](https://github.com/xojs/xo).

### Other Configs

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Adjunct](https://github.com/davidjbradshaw/eslint-config-adjunct) - A reasonable collection of plugins to use alongside your main ESLint configuration.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Ash-Nazg](https://github.com/brettz9/eslint-config-ash-nazg) - One config to rule them all!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Cecilia](https://github.com/SandroMiguel/eslint-config-cecilia) - ESLint configuration for awesome projects.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [ES](https://github.com/thenativeweb/eslint-config-es) - Shareable config for very strict code.
- <b><code>&nbsp;&nbsp;&nbsp;150⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Hardcore](https://github.com/EvgenyOrekhov/eslint-config-hardcore) - The most strict (but practical) ESLint config out there.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;61⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Problems](https://github.com/RyanZim/eslint-config-problems) - Shareable config that only catches actual problems, and doesn't enforce stylistic preferences.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Supermind](https://github.com/supermind/eslint-config-supermind) - Shareable config for Supermind style.

## Preconfigured Configs with ESLint Set up

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Node.js Standard Style](https://github.com/geek/node-style) - Node.js core config.
- <b><code>&nbsp;&nbsp;&nbsp;845⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;59🍴</code></b> [prettier-standard](https://github.com/sheerun/prettier-standard) - Prettier formatter with custom eslint rules allowed.
- <b><code>&nbsp;26731⭐</code></b> <b><code>&nbsp;&nbsp;2180🍴</code></b> [Standard](https://github.com/feross/standard) - JavaScript Standard Style.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Superlint](https://github.com/supermind/superlint) - JavaScript Supermind Style.
- <b><code>&nbsp;&nbsp;6459⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;322🍴</code></b> [XO](https://github.com/sindresorhus/xo) - JavaScript happiness style linter ❤️.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;72⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Healthier](https://github.com/KidkArolis/healthier) - Code style agnostic version of Standard, perfect companion to Prettier.

## Plugins

### Code Quality

- <b><code>&nbsp;&nbsp;&nbsp;155⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62🍴</code></b> [GitHub](https://github.com/github/eslint-plugin-github) - Misc. rules from GitHub.
- <b><code>&nbsp;&nbsp;&nbsp;689⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [SonarJS](https://github.com/SonarSource/eslint-plugin-sonarjs) - Rules detecting bugs and suspicious patterns.
- <b><code>&nbsp;&nbsp;2332⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;278🍴</code></b> [Unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn) - Various awesome ESLint rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [@mysticatea/eslint-plugin](https://github.com/mysticatea/eslint-plugin) - Misc. rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [@brettz9/eslint-plugin](https://github.com/brettz9/eslint-plugin) - Misc. rules. of `@mysticatea` without the personal config.

### Compatibility

- <b><code>&nbsp;&nbsp;2767⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Compat](https://github.com/amilajack/eslint-plugin-compat) - Lint browser compatibility of APIs used  🌎 [caniuse](http://caniuse.com/#search=fetch) as an ESLint plugin).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ecmascript-compat](https://github.com/robatwilliams/es-compat) - Disable ECMAScript language features not supported by your browserslist targets.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;83⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [es](https://github.com/mysticatea/eslint-plugin-es) - Disable specific ECMAScript language versions or individual features.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [es5](https://github.com/nkt/eslint-plugin-es5) - ESLint plugin for ES5 users (forbid ES2015+ usage).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [ie11](https://github.com/Volox/eslint-plugin-ie11) - Detect unsupported ES6 features in IE11.

### CSS in JS

- <b><code>&nbsp;&nbsp;&nbsp;125⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [CSS-modules](https://github.com/atfzl/eslint-plugin-css-modules) - Lint undefined or unused rules for css modules.
- <b><code>&nbsp;14571⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;953🍴</code></b> [Emotion](https://github.com/emotion-js/emotion/tree/master/packages/eslint-plugin) - ESLint rules for emotion.
- Styled Components
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;53⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [Better Styled Components](https://github.com/tinloof/eslint-plugin-better-styled-components) - Auto fixable ESlint's rules for styled components.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [styled-components-a11y](https://github.com/brendanmorrell/eslint-plugin-styled-components-a11y) - A11y for Styled Components.

### Deprecation

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;63⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [deprecate](https://github.com/AlexMost/eslint-plugin-deprecate) - Mark functions or modules as deprecated and get lint messages when they are used.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19🍴</code></b> [deprecation](https://github.com/gund/eslint-plugin-deprecation) - Identifies use of
  jsdoc `@deprecated` functions.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [disable](https://github.com/mradionov/eslint-plugin-disable) - Disable specified plugins using file path patterns and inline comments.

### Embedded

- <b><code>&nbsp;&nbsp;&nbsp;359⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49🍴</code></b> [HTML](https://github.com/BenoitZugmeyer/eslint-plugin-html) - Linting for JavaScript inside of HTML `<script>` tags.
- <b><code>&nbsp;&nbsp;&nbsp;273⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Markdown](https://github.com/eslint/eslint-plugin-markdown) - Linting for JavaScript inside of Markdown.

### Frameworks

- <b><code>&nbsp;&nbsp;&nbsp;611⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;132🍴</code></b> [AngularJS](https://github.com/Gillespie59/eslint-plugin-angular) - Linting rules to adhere to the <b><code>&nbsp;24124⭐</code></b> <b><code>&nbsp;&nbsp;4332🍴</code></b> [John Papa's AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Backbone](https://github.com/ilyavolodin/eslint-plugin-backbone) - Linting rules for Backbone.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [Custom Elements](https://github.com/github/eslint-plugin-custom-elements) - Rules by GitHub for Custom Elements.
- <b><code>&nbsp;&nbsp;&nbsp;251⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;179🍴</code></b> [Ember](https://github.com/ember-cli/eslint-plugin-ember) - Linting rules for Ember.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Hapi](https://github.com/continuationlabs/eslint-plugin-hapi) - Linting rules for hapi.
- <b><code>&nbsp;&nbsp;&nbsp;115⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;22🍴</code></b> [Meteor](https://github.com/dferber90/eslint-plugin-meteor) - Meteor specific linting rules.
- React
  - <b><code>&nbsp;&nbsp;2703⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;554🍴</code></b> [JSX a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y) - Accessibility rules on JSX elements.
  - <b><code>&nbsp;&nbsp;7643⭐</code></b> <b><code>&nbsp;&nbsp;2384🍴</code></b> [React](https://github.com/yannickcr/eslint-plugin-react) - Linting rules for React and JSX.
  - <b><code>183667⭐</code></b> <b><code>&nbsp;37569🍴</code></b> [React Hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - Linting rules for React Hooks.
  - <b><code>&nbsp;&nbsp;&nbsp;634⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [React Native](https://github.com/Intellicode/eslint-plugin-react-native) - React Native specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17🍴</code></b> [React-Redux](https://github.com/DianaSuvorova/eslint-plugin-react-redux) - React-Redux specific linting rules.
- <b><code>&nbsp;&nbsp;&nbsp;316⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40🍴</code></b> [Svelte](https://github.com/sveltejs/eslint-plugin-svelte3) - Linting rules for Svelte v3 Components.
- Vue
  - <b><code>&nbsp;&nbsp;3642⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;558🍴</code></b> [VueJS](https://github.com/vuejs/eslint-plugin-vue) - Plugin for VueJS.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [VueJS Scoped CSS](https://github.com/future-architect/eslint-plugin-vue-scoped-css) - Plugin for Scoped CSS in VueJS.

### Languages and Environments

- 🌎 [AssemblyScript](https://www.npmjs.com/package/@shopify/eslint-plugin-assemblyscript) - Rules for enforcing restrictions on TypeScript toward AssemblyScript compliance.
- <b><code>&nbsp;&nbsp;&nbsp;113⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [eslint-plugin-eslint-plugin](https://github.com/not-an-aardvark/eslint-plugin-eslint-plugin) - An ESLint plugin for linting ESLint plugins.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Coffee](https://github.com/aminland/eslint-plugin-coffee) - Enables linting CoffeeScript files with, with optional linting rules from the Coffeelint library.
- Flow
  - <b><code>&nbsp;&nbsp;1070⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;163🍴</code></b> [Flow](https://github.com/gajus/eslint-plugin-flowtype) - Flow type linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;405⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Flow Errors](https://github.com/amilajack/eslint-plugin-flowtype-errors) - Run Flow as an ESLint plugin.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;60⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [HTML](https://github.com/yeonjuan/html-eslint) - ESLint plugin for HTML.
- JSON
  - <b><code>&nbsp;&nbsp;&nbsp;148⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23🍴</code></b> [JSON](https://github.com/azeemba/eslint-plugin-json) - Lint your JSON files.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [JSON, package.json](https://github.com/Bkucera/eslint-plugin-json-format) - Lint, format, and auto-fix your JSON files. Sort your `package.json`.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [JSON with Comments](https://github.com/ota-meshi/eslint-plugin-jsonc) - ESLint plugin for JSON, JSONC and JSON5.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [JSON Schema](https://github.com/ota-meshi/eslint-plugin-json-schema-validator) - Validates data defined in JavaScript, JSON, YAML and TOML using JSON Schema Validator.
- <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15🍴</code></b> [MDX](https://github.com/mdx-js/eslint-mdx/tree/master/packages/eslint-plugin-mdx) - ESLint Parser/Plugin for MDX.
- <b><code>&nbsp;&nbsp;&nbsp;848⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;128🍴</code></b> [Node](https://github.com/mysticatea/eslint-plugin-node) - Additional ESLint's rules for Node.js.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [SQL](https://github.com/gajus/eslint-plugin-sql) - SQL linting rules for ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [TOML](https://github.com/ota-meshi/eslint-plugin-toml) - ESLint plugin for TOML.
- <b><code>&nbsp;11187⭐</code></b> <b><code>&nbsp;&nbsp;2049🍴</code></b> [TypeScript](https://github.com/typescript-eslint/typescript-eslint/tree/master/packages/eslint-plugin) - Linting rules for TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [YAML](https://github.com/ota-meshi/eslint-plugin-yml) - ESLint plugin for YAML.

### Libraries

- GraphQL
  - <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [dotansimha/graphql-eslint](https://github.com/dotansimha/graphql-eslint) - Validates, prettifies and checks your GraphQL operations and GraphQL schema for best-practices.
  - <b><code>&nbsp;&nbsp;1154⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [apollostack/eslint-plugin-graphql](https://github.com/apollostack/eslint-plugin-graphql) - Check your GraphQL query strings against a schema.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [TypeGraphQL](https://github.com/borremosch/eslint-plugin-type-graphql) - Linting rules for TypeGraphQL, targeted at finding common mistakes.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [jQuery](https://github.com/wikimedia/eslint-plugin-no-jquery) - Linting rules for jQuery, including versioned configs for deprecated features.
- <b><code>&nbsp;&nbsp;&nbsp;663⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;117🍴</code></b> [JSDoc](https://github.com/gajus/eslint-plugin-jsdoc) - Linting rules for JSDoc comments (including the JavaScript within `@example`).
- Lodash
  - <b><code>&nbsp;&nbsp;&nbsp;234⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64🍴</code></b> [Lodash](https://github.com/wix/eslint-plugin-lodash) - Lodash specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28🍴</code></b> [Lodash/fp](https://github.com/jfmengels/eslint-plugin-lodash-fp) - Lodash/fp specific linting rules.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Lodash template](https://github.com/ota-meshi/eslint-plugin-lodash-template) - Plugin for Lodash template/Underscore template.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Microtemplates](https://github.com/platinumazure/eslint-plugin-microtemplates) (Used in Lodash and Underscore.js)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Mongodb](https://github.com/nfroidure/eslint-plugin-mongodb) - Mongodb native Node.js driver linting rules.
- <b><code>&nbsp;&nbsp;&nbsp;116⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [Ramda](https://github.com/ramda/eslint-plugin-ramda) - Ramda specific linting rules.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;28⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [RequireJS](https://github.com/cvisco/eslint-plugin-requirejs) - Linting rules for RequireJS.

### Misc

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [Diff](https://github.com/paleite/eslint-plugin-diff) - Run ESLint on your changed lines only. Also supports CI!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [Notice](https://github.com/nickdeis/eslint-plugin-notice) - An eslint rule that checks the top of files and fixes them too!
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Only-Error](https://github.com/davidjbradshaw/eslint-plugin-only-error) - Convert all rules to errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;97⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Only-Warn](https://github.com/bfanger/eslint-plugin-only-warn) - Convert all rules to warnings.
- <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [PutOut](https://github.com/coderaiser/putout/tree/master/packages/eslint-plugin-putout) - an ESLint plugin integrates <b><code>&nbsp;&nbsp;&nbsp;255⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18🍴</code></b> [putout](https://github.com/coderaiser/putout) linter into ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;172⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6🍴</code></b> [TypeLint](https://github.com/yarax/eslint-plugin-typelint) - Introduces types, based on existing schemas (Swagger, Redux) and linting access to object properties, preventing `undefined` errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Woke](https://github.com/amwmedia/eslint-plugin-woke) - Helps catch insensitive words, promoting an inclusive codebase.

### Practices and Specific ES Features

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [array-func](https://github.com/freaktechnik/eslint-plugin-array-func) - Avoid redundancy when using es2015 array methods and functions.
- <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [arrow functions](https://github.com/getify/eslint-plugin-proper-arrows) - ESLint rules to ensure proper arrow function definitions.
- <b><code>&nbsp;40512⭐</code></b> <b><code>&nbsp;&nbsp;5239🍴</code></b> [Babel](https://github.com/babel/babel/tree/main/eslint/babel-eslint-plugin) - Adds replacements for built-in rules to include Babel features.
- <b><code>&nbsp;&nbsp;&nbsp;235⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [boundaries](https://github.com/javierbrea/eslint-plugin-boundaries) - Ensures that your architecture boundaries are respected by the elements in your project checking file structure and dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;267⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;36🍴</code></b> [ESLint Comments](https://github.com/mysticatea/eslint-plugin-eslint-comments) - Best practices about ESLint directive comments (`/*eslint-disable*/`, etc.).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [eslint-plugin-write-good-comments](https://github.com/kantord/eslint-plugin-write-good-comments) - Enforce good writing style in comments.
- <b><code>&nbsp;&nbsp;&nbsp;913⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [fp](https://github.com/jfmengels/eslint-plugin-fp) - ESLint rules for functional programming.
- <b><code>&nbsp;&nbsp;&nbsp;462⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [functional](https://github.com/jonaskello/eslint-plugin-functional) - ESLint rules to disable mutation and promote fp in JavaScript and TypeScript.
- <b><code>&nbsp;&nbsp;&nbsp;902⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25🍴</code></b> [Immutable](https://github.com/jhusain/eslint-plugin-immutable) - Disable all mutation in JavaScript.
- <b><code>&nbsp;&nbsp;3869⭐</code></b> <b><code>&nbsp;&nbsp;1276🍴</code></b> [import](https://github.com/benmosher/eslint-plugin-import) - Linting of ES2015+ import/export syntax, and prevent issues with misspelling of file paths and import names.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [new-with-error](https://github.com/Trott/eslint-plugin-new-with-error) - Require errors to be thrown using `new`.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [no-constructor-bind](https://github.com/markalfred/eslint-plugin-no-constructor-bind) - Encourages use of class properties by reporting use of `this` with `bind` or setting state in constructors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [no-inferred-method-name](https://github.com/johnstonbl01/eslint-no-inferred-method-name) - Custom rule for ESLint that checks for inferred method names within object literals.
- <b><code>&nbsp;&nbsp;&nbsp;104⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [no-loops](https://github.com/buildo/eslint-plugin-no-loops) - It's 2019 and you still use loops?
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [no-restricted-syntax](https://github.com/brettz9/eslint-plugin-query) - Show queried syntax's content in messages.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;49⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [no-use-extend-native](https://github.com/dustinspecker/eslint-plugin-no-use-extend-native) - Prevent using extended native objects.
- <b><code>&nbsp;&nbsp;&nbsp;696⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [Promise](https://github.com/xjamundx/eslint-plugin-promise) - Best practices when working with promises.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [pure](https://github.com/purely-functional/eslint-plugin-pure) - Enforce pure functions (without side effects).
- <b><code>&nbsp;&nbsp;&nbsp;158⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [RegExp](https://github.com/ota-meshi/eslint-plugin-regexp) - ESLint plugin for finding regexp mistakes and style guide violations.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;65⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13🍴</code></b> [sort-keys-fix](https://github.com/leo-buneev/eslint-plugin-sort-keys-fix) - Adds fixer for ESLint `sort-keys` rule.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [this](https://github.com/matijs/eslint-plugin-this) - Write pure functions, don't allow `this`.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [toplevel](https://github.com/HKalbasi/eslint-plugin-toplevel) - An eslint plugin for disallow side effect at module toplevel.

### Performance

- <b><code>&nbsp;&nbsp;&nbsp;278⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [clean-regex](https://github.com/RunDevelopment/eslint-plugin-clean-regex) - JavaScript regex linter that aims to help write better regular expressions by pointing out errors and suggesting improvements.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [DOM](https://github.com/amilajack/eslint-plugin-dom)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;56⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [Optimize Regex](https://github.com/BrainMaestro/eslint-plugin-optimize-regex) - Optimize regex literals.
- Perf-Standard <b><code>&nbsp;&nbsp;&nbsp;&nbsp;19⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [plugin](https://github.com/Raynos/eslint-plugin-perf-standard) and <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Config](https://github.com/Raynos/eslint-config-perf-standard)

### Security

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;88⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [no-secrets](https://github.com/nickdeis/eslint-plugin-no-secrets) - An eslint plugin that detects potential secrets/credentials.
- <b><code>&nbsp;&nbsp;&nbsp;146⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [no-unsanitized](https://github.com/mozilla/eslint-plugin-no-unsanitized) - Checks for `innerHTML`, `outerHTML`, etc.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [pii](https://github.com/shiva-hack/eslint-plugin-pii) - Checks and enforces PII Compliance of the code. i.e. no email address, birth date, IP address or phone number in comments or string literals.
- ScanJS <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11🍴</code></b> [config](https://github.com/mozfreddyb/eslint-config-scanjs) and <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [plugin](https://github.com/mozfreddyb/eslint-plugin-scanjs-rules) - Security-related rules.
- <b><code>&nbsp;&nbsp;1677⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;110🍴</code></b> [Security](https://github.com/nodesecurity/eslint-plugin-security) - ESLint rules for Node Security.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;46⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10🍴</code></b> [xss](https://github.com/Rantanen/eslint-plugin-xss) - Tries to detect XSS issues in codebase before they end up in production.

### Style

- 🌎 [const case](https://www.npmjs.com/package/eslint-plugin-const-case) - Enforce capitalization of constant primitive literals.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [editorconfig](https://github.com/platinumazure/eslint-plugin-editorconfig) - Derive rules from 🌎 [`.editorconfig`](https://editorconfig.org/).
- <b><code>&nbsp;&nbsp;&nbsp;242⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30🍴</code></b> [filenames](https://github.com/selaux/eslint-plugin-filenames) - Ensure consistent filenames for your JavaScript files.
- <b><code>&nbsp;&nbsp;&nbsp;864⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;48🍴</code></b> [Simple import sort](https://github.com/lydell/eslint-plugin-simple-import-sort) - Easy autofixable import sorting.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Switch case](https://github.com/lukeapage/eslint-plugin-switch-case) - Switch-case-specific linting rules for ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [padding](https://github.com/mu-io/eslint-plugin-padding) - Allows/disallows padding between statements.

### Testing Tools

- <b><code>&nbsp;&nbsp;&nbsp;221⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [AVA](https://github.com/avajs/eslint-plugin-ava) - Linting rules for AVA.
- Chai
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [expect practices](https://github.com/turbo87/eslint-plugin-chai-expect)
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;47⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [with unused expressions](https://github.com/ihordiachenko/eslint-plugin-chai-friendly)
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [permitted keywords](https://github.com/gavinaiken/eslint-plugin-chai-expect-keywords)
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [with chai-as-promised plugin](https://github.com/fintechstudios/eslint-plugin-chai-as-promised)
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [Cucumber](https://github.com/darrinholst/eslint-plugin-cucumber) - Linting rules for Cucumber.
- <b><code>&nbsp;&nbsp;&nbsp;518⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51🍴</code></b> [Cypress](https://github.com/cypress-io/eslint-plugin-cypress) - Linting rules for Cypress.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;91⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;50🍴</code></b> [Jasmine](https://github.com/tlvince/eslint-plugin-jasmine) - Linting rules for Jasmine.
- Jest
  - <b><code>&nbsp;&nbsp;&nbsp;871⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;175🍴</code></b> [Enforcing practices](https://github.com/jest-community/eslint-plugin-jest) - Linting rules for Jest.
  - <b><code>&nbsp;&nbsp;&nbsp;111⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9🍴</code></b> [Enforcing consistent formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) - Formatting rules for Jest.
  - 🌎 [Jest-async](https://www.npmjs.com/package/eslint-plugin-jest-async) - Async linting rule for Jest.
  - <b><code>&nbsp;&nbsp;&nbsp;243⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29🍴</code></b> [Jest-DOM](https://github.com/testing-library/eslint-plugin-jest-dom) - Linting rules for Jest-DOM.
- Mocha
  - <b><code>&nbsp;&nbsp;&nbsp;265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;68🍴</code></b> [Enforcing practices](https://github.com/lo1tuma/eslint-plugin-mocha) - Linting rules for Mocha.
  - <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Enforcing manageability](https://github.com/onechiporenko/eslint-plugin-mocha-cleanup/)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16🍴</code></b> [QUnit](https://github.com/platinumazure/eslint-plugin-qunit) - Linting rules for QUnit.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [TestCafe-Community](https://github.com/testcafe-community/eslint-plugin-testcafe-community) - TestCafe linting rules with env globals (fork from <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe)).
- <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;66🍴</code></b> [Testing Library](https://github.com/testing-library/eslint-plugin-testing-library) - Linting rules for Testing Library.

## Parsers

- <b><code>&nbsp;&nbsp;2969⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;229🍴</code></b> [Babel](https://github.com/babel/babel-eslint) - Use Babel's parser for linting all Babel features.
- <b><code>&nbsp;11187⭐</code></b> <b><code>&nbsp;&nbsp;2049🍴</code></b> [TypeScript](https://github.com/typescript-eslint/typescript-eslint) - A TypeScript parser that produces output compatible with ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8🍴</code></b> [BrightScript](https://github.com/RokuRoad/eslint-plugin-roku) - BrightScript plugin for Roku development. Includes Parser and Rules.
- <b><code>&nbsp;&nbsp;&nbsp;408⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [GraphQL](https://github.com/dotansimha/graphql-eslint) - Parser for the GraphQL AST. Includes parser, plugin, processor (for non-graphql files) and rules.

## Formatters

<!-- ignore is to keep "github" lower-case -->
<!--lint ignore awesome-spell-check-->

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [badger](https://github.com/brettz9/eslint-formatter-badger) - Make SVG-based badges summarizing ESLint results (e.g., for use on a README).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [git-log](https://github.com/JamieMason/eslint-formatter-git-log) - ESLint Formatter featuring Git Author, Date, and Hash.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [github](https://github.com/hipstersmoothie/eslint-formatter-github) - See ESLint errors and warnings directly in pull requests.
- 🌎 [gitlab](https://gitlab.com/remcohaszing/eslint-formatter-gitlab) - Output ESLint results in the GitLab code quality results.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [mo](https://github.com/fengzilong/eslint-formatter-mo) - Good-lookin' ESLint formatter and also for delightful reading experience.
- 🌎 [SARIF](https://www.npmjs.com/package/@microsoft/eslint-formatter-sarif) - Generate a results in a SARIF format so it can be imported into tools like GitHub Advanced Security.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [summary-chart](https://github.com/davidjbradshaw/eslint-formatter-summary-chart) - Format ESLint output into a bar chart.

## Globals

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [Restricted Globals](https://github.com/sidoshi/eslint-restricted-globals) - Expect `window` qualifier on globals that may otherwise be confusable as local variables.
- <b><code>&nbsp;&nbsp;&nbsp;236⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;101🍴</code></b> [ES and browser globals](https://github.com/sindresorhus/globals) (originally from ESLint)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [chai globals](https://github.com/t-huth/eslint-plugin-chai-assert-bdd)
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7🍴</code></b> [TestCafe globals](https://github.com/miherlosev/eslint-plugin-testcafe) - `fixture` & `test` globals for TestCafe.

## Tools

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;55⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [eslint-define-config](https://github.com/Shinigami92/eslint-define-config) - Provide a `defineConfig` function for `.eslintrc.js` files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [es-file-traverse](https://github.com/brettz9/es-file-traverse) - Obtain a list of only those files which are in use based on imports and/or requires from an entry file or files; list passable to ESLint. Intended esp. for linting 3rd party dependencies.
- <b><code>&nbsp;&nbsp;&nbsp;174⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33🍴</code></b> [eslint-find-rules](https://github.com/sarbbottam/eslint-find-rules) - Find built-in ESLint rules you don't have in your custom config.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4🍴</code></b> [eslint-index](https://github.com/wagerfield/eslint-index) - CLI for finding and managing rules in ESLint config files.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2🍴</code></b> [eslint-interactive](https://github.com/mizdra/eslint-interactive) - The CLI tool to fix huge number of ESLint errors.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [eslint-multiplexer](https://github.com/pimlie/eslint-multiplexer) - Multiplex eslint results and merge results for common files.
- <b><code>&nbsp;&nbsp;&nbsp;475⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;27🍴</code></b> [eslint-nibble](https://github.com/IanVS/eslint-nibble) - Ease into ESLint, by fixing one rule at a time.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;32🍴</code></b> [eslint-rule-documentation](https://github.com/jfmengels/eslint-rule-documentation) - Find the url for the documentation of an ESLint rule.
- <b><code>&nbsp;&nbsp;&nbsp;173⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24🍴</code></b> [eslint-watch](https://github.com/rizowski/eslint-watch) - Run ESLint with watch mode.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [codacy-eslint](https://github.com/codacy/codacy-eslint) - Docker used at 🌎 [Codacy](https://www.codacy.com) to run ESLint.
- <b><code>&nbsp;&nbsp;&nbsp;618⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44🍴</code></b> [esprint](https://github.com/pinterest/esprint) - Run ESLint across multiple threads.
- <b><code>&nbsp;&nbsp;&nbsp;144⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [generator-eslint](https://github.com/eslint/generator-eslint) - Generate ESLint
  plugin and rules with 🌎 [Yeoman](http://yeoman.io/).
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [editor-info](https://github.com/fisker/editor-info) - Detect whether one is within an editor/IDE and which type, allowing one to tweak ESLint configuration accordingly.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1🍴</code></b> [eslint-dashboard](https://github.com/fengzilong/eslint-dashboard) - Interactive ESLint workflow that lives in your terminal.
- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;90⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5🍴</code></b> [eslint-remote-tester](https://github.com/AriPerkkio/eslint-remote-tester) - CLI tool for testing given ESlint rules against multiple repositories at once.

## Developing for ESLint

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3🍴</code></b> [eslint-docs](https://github.com/j-f1/eslint-docs) - Keep your rule descriptions up-to-date across the repository.

## Tutorials

- 🌎 [Creating an ESLint Plugin](https://medium.com/tumblbug-engineering/creating-an-eslint-plugin-87f1cb42767f) - Article walking through the creation of an ESLint rule and plugin.
- 🌎 [Lint Like It's 2015](https://medium.com/@dan_abramov/lint-like-it-s-2015-6987d44c5b48#.5p3yk0b03) - Article walking through the benefits of using ESLint.
- 🌎 [Linting JavaScript with ESLint](https://egghead.io/lessons/javascript-linting-javascript-with-eslint) - Video showing ESLint setup and basics.
- 🌎 [Linting React JSX with ESLint (in ES6)](https://egghead.io/lessons/react-linting-react-jsx-with-eslint-in-es6) - Video showing how to use React and JSX with ESLint.
- 🌎 [Plugin Module with Mixins](https://chrysanthium.com/eslint-integration) - Article on how to write a plugin as a node module containing modular mixin configuration.
- 🌎 [Writing a rule to spot undeclared props hiding in plain sight](http://blog.cowchimp.com/writing-a-custom-eslint-rule-to-spot-undeclared-props/) - Article about creating rules that require scope analysis.

## Installation and Setup

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0🍴</code></b> [Lintier](https://github.com/josh-stillman/lintier) - CLI to quickly scaffold an ESLint & Prettier setup in a TypeScript project.

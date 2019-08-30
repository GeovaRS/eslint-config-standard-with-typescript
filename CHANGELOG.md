# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [9.0.0](https://github.com/standard/eslint-config-standard-with-typescript/compare/v8.0.0...v9.0.0) (2019-08-30)


### ⚠ BREAKING CHANGES

* added rule `@typescript-eslint/no-misused-promises` https://github.com/typescript-eslint/typescript-eslint/commit/28a131d
* added rule `@typescript-eslint/require-await` https://github.com/typescript-eslint/typescript-eslint/commit/807bc2d
* added rule `@typescript-eslint/prefer-readonly` https://github.com/typescript-eslint/typescript-eslint/commit/76b89a5
* added rule `@typescript-eslint/strict-boolean-expressions` https://github.com/typescript-eslint/typescript-eslint/commit/34e7d1e
* replaced rule `@typescript-eslint/no-triple-slash-reference` with `@typescript-eslint/no-reference-import` https://github.com/typescript-eslint/typescript-eslint/commit/af70a59
* eslint-config-standard@^14.0.0
* new rule: `@typescript-eslint/no-floating-promises: error`: https://github.com/typescript-eslint/typescript-eslint/blob/v1.11.0/packages/eslint-plugin/docs/rules/no-floating-promises.md
* new rule: `@typescript-eslint/no-empty-function: error`: https://github.com/typescript-eslint/typescript-eslint/blob/v1.11.0/packages/eslint-plugin/docs/rules/no-empty-function.md

* standard v14 ([51f4581](https://github.com/standard/eslint-config-standard-with-typescript/commit/51f4581))


### Bug Fixes

* [no-unused-vars] Allow unused parameters ([5b70896](https://github.com/standard/eslint-config-standard-with-typescript/commit/5b70896))
* [no-use-before-define] Disable eslint version ([9d9c792](https://github.com/standard/eslint-config-standard-with-typescript/commit/9d9c792))
* add ESLint to the list of dependencies ([4600a95](https://github.com/standard/eslint-config-standard-with-typescript/commit/4600a95))
* add missing eslint dependency to readme.md ([501ba09](https://github.com/standard/eslint-config-standard-with-typescript/commit/501ba09))
* drop peerDependency of eslint-config-standard ([85d7174](https://github.com/standard/eslint-config-standard-with-typescript/commit/85d7174)), closes [#131](https://github.com/standard/eslint-config-standard-with-typescript/issues/131)
* loosen explicit-function-return-type ([bdae116](https://github.com/standard/eslint-config-standard-with-typescript/commit/bdae116)), closes [#110](https://github.com/standard/eslint-config-standard-with-typescript/issues/110)
* remove explicit-member-accessibility ([f673d9d](https://github.com/standard/eslint-config-standard-with-typescript/commit/f673d9d)), closes [#111](https://github.com/standard/eslint-config-standard-with-typescript/issues/111)
* sort the rules by type ([4e48fdc](https://github.com/standard/eslint-config-standard-with-typescript/commit/4e48fdc))
* update readme to reflect correct usage ([8a29b9e](https://github.com/standard/eslint-config-standard-with-typescript/commit/8a29b9e))
* **tsconfig.json:** utilize new tsconfig.eslint.json file ([fb0976d](https://github.com/standard/eslint-config-standard-with-typescript/commit/fb0976d))


### Features

* @typescript-eslint/eslint-plugin@^1.11.0 ([ad3f043](https://github.com/standard/eslint-config-standard-with-typescript/commit/ad3f043)), closes [#99](https://github.com/standard/eslint-config-standard-with-typescript/issues/99)
* @typescript-eslint/eslint-plugin@^1.12.0 ([b41f0e5](https://github.com/standard/eslint-config-standard-with-typescript/commit/b41f0e5)), closes [#100](https://github.com/standard/eslint-config-standard-with-typescript/issues/100)
* @typescript-eslint/eslint-plugin@^1.13.0 ([72fc639](https://github.com/standard/eslint-config-standard-with-typescript/commit/72fc639)), closes [#101](https://github.com/standard/eslint-config-standard-with-typescript/issues/101)
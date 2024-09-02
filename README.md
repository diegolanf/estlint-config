# ESLint Rules

This repository contains an ESLint configuration file authored and maintained by developers in Medialesson. The provided
configuration aims to adhere to industry best practices and company-specific coding standards, ensuring consistency,
maintainability, and quality across all projects.

## Recommended rules

### ESLint

Recommended rules are enabled.

For more information see: https://eslint.org/docs/latest/rules/#suggestions

### typescript-eslint

Recommended rules are enabled.

For more information see: https://typescript-eslint.io/rules/

### angular-eslint

Recommended rules are enabled.

For more information see: https://github.com/angular-eslint/angular-eslint

### nx

Default rules are enabled.

## Custom enabled rules

| Rule name                                                                                                                                                                              | Description                                                                                                  | Additional information                                                                  | autofix |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------- |
| [eqeqeq](https://eslint.org/docs/latest/rules/eqeqeq)                                                                                                                                  | Require the use of `===` and `!==`.                                                                          |                                                                                         | ❌      |
| [spaced-comment](https://eslint.org/docs/latest/rules/spaced-comment)                                                                                                                  | Enforce consistent spacing after the `//` or `/*` in a comment.                                              |                                                                                         | ✅      |
| [no-console](https://eslint.org/docs/latest/rules/no-console)                                                                                                                          | Warn about the use of `console`.                                                                             | Use a LoggerService instead.                                                            | ❌      |
| [@angular-eslint/component-selector](https://github.com/angular-eslint/angular-eslint/blob/main/packages/eslint-plugin/docs/rules/component-selector.md)                               | Require components to be kebab-case and to have a specific name (set per app/lib).                           |                                                                                         | ❌      |
| [@angular-eslint/directive-selector](https://github.com/angular-eslint/angular-eslint/blob/main/packages/eslint-plugin/docs/rules/directive-selector.md)                               | Require directives to be camelCase and to have a specific name (set per app/lib).                            |                                                                                         | ❌      |
| [@angular-eslint/template/attributes-order](https://github.com/angular-eslint/angular-eslint/blob/main/packages/eslint-plugin-template/docs/rules/attributes-order.md)                 | Ensures that HTML attributes and Angular bindings are sorted based on an expected order.                     |                                                                                         | ✅      |
| [@angular-eslint/template/eqeqeq](https://github.com/angular-eslint/angular-eslint/blob/main/packages/eslint-plugin-template/docs/rules/eqeqeq.md)                                     | Requires `===` and `!==` in place of `==` and `!=`.                                                          |                                                                                         | ✅      |
| [@angular-eslint/template/prefer-self-closing-tags](https://github.com/angular-eslint/angular-eslint/blob/main/packages/eslint-plugin-template/docs/rules/prefer-self-closing-tags.md) | Ensures that self-closing tags are used for elements with a closing tag but no content.                      |                                                                                         | ✅      |
| [@typescript-eslint/explicit-function-return-type](https://typescript-eslint.io/rules/explicit-function-return-type/)                                                                  | Require explicit return types on functions and class methods.                                                |                                                                                         | ❌      |
| [@typescript-eslint/explicit-member-accessibility](https://typescript-eslint.io/rules/explicit-member-accessibility)                                                                   | Require explicit accessibility modifiers on class properties and methods.                                    | Disallows use of `public`.                                                              | ✅      |
| [@typescript-eslint/lines-around-comment](https://eslint.org/docs/latest/rules/lines-around-comment)                                                                                   | Require empty lines before and/or after comments.                                                            |                                                                                         | ✅      |
| [@typescript-eslint/lines-between-class-members](https://typescript-eslint.io/rules/lines-between-class-members)                                                                       | Require or disallow an empty line between class members.                                                     |                                                                                         | ✅      |
| [@typescript-eslint/member-ordering](https://typescript-eslint.io/rules/member-ordering)                                                                                               | Require a consistent member declaration order.                                                               |                                                                                         | ❌      |
| [@typescript-eslint/no-inferrable-types](https://typescript-eslint.io/rules/no-inferrable-types)                                                                                       | Disallow explicit type declarations for variables or parameters initialized to a number, string, or boolean. |                                                                                         | ❌      |
| [@typescript-eslint/no-invalid-this](https://typescript-eslint.io/rules/no-invalid-this)                                                                                               | Disallow `this` keywords outside of classes or class-like objects.                                           |                                                                                         | ❌      |
| [@typescript-eslint/no-unused-vars](https://typescript-eslint.io/rules/no-unused-vars)                                                                                                 | Disallow unused vars.                                                                                        |                                                                                         | ❌      |
| [import/no-absolute-path](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-absolute-path.md)                                                                  | Disallow the import of modules using absolute paths.                                                         |                                                                                         | ✅      |
| [import/no-cycle](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-cycle.md)                                                                                  | Ensures that there is no resolvable path back to this module via its dependencies.                           |                                                                                         | ❌      |
| [import/no-self-import](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-self-import.md)                                                                      | Forbid a module from importing itself.                                                                       |                                                                                         | ❌      |
| [import/no-useless-path-segments](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-useless-path-segments.md)                                                  | Prevents unnecessary path segments in import and require statements.                                         |                                                                                         | ✅      |
| [simple-import-sort/imports](https://github.com/lydell/eslint-plugin-simple-import-sort)                                                                                               | Require sorting of imports.                                                                                  | Helps to prevent merge conflicts, errors can be ignored as they're fixed automatically. | ✅      |
| [simple-import-sort/exports](https://github.com/lydell/eslint-plugin-simple-import-sort)                                                                                               | Require sorting of exports.                                                                                  |                                                                                         | ✅      |

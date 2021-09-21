# JavaScript

- Use the latest stable JavaScript syntax with a transpiler, e.g., [babel], [swc].
- Use [ESLint] and [Prettier] for auto-formatting and auto-fixing
- Prefer ES6 classes over prototypes.
- Use strict equality checks (`===` and `!==`) except when comparing against
  (`null` or `undefined`).
- Prefer ES6 [destructuring] over object literal notation.
- Use ES6 [spread] and [rest] operator wherever possible for a cleaner code.
- Use `PascalCase` for classes, `lowerCamelCase` for variables and functions,
  `SCREAMING_SNAKE_CASE` for constants, `_singleLeadingUnderscore` for private
  variables and functions.
- Prefer [template strings] over string concatenation.
- Prefer promises over callbacks.
- Prefer array functions like `map` and `forEach` over `for` loops.
- Use `const` for declaring variables that will never be re-assigned, and `let`
  otherwise.
- Avoid `var` to declare variables.
- Use classes with `js-` prefix when targeting HTML elements.
- Avoid targeting HTML elements using classes intended for styling purposes.

[babel]: https://babeljs.io/
[destructuring]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment
[eslint]: https://eslint.org/
[prettier]: https://prettier.io/
[rest]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters
[spread]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
[swc]: https://swc.rs
[template strings]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/template_strings

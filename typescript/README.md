# TypeScript

- Use the guidelines for [JavaScript](/javascript/)
- Use TypeScript in [strict mode]
- Use [ESLint] and [Prettier] for auto-formatting and auto-fixing
- Prefer [Functions] over [Classes]
- Prefer functional style (map/filter/reduce) over iteration (for/while/.each)
- Use [Generic Constraints] when possible
- Use `PascalCase` for [Interfaces] and [Type Aliases]
- Use [readonly] properties where applicable
- Use [Const Assertions] where applicable to avoid type widening
- Avoid complex conditionals inside TSX
- Avoid [Mixins]
- Avoid [Decorators]
- Avoid [Overloading Functions]
- Prefer [async/await] over traditional promise syntax
- Prefer [Optional Properties] in an interface rather than declaring the
  property type as `T | undefined`
- Prefer explicitly defining interfaces over [Extending Interfaces]
- Avoid the use of the [any] type
- Avoid the [Non-null assertion operator]
- Avoid [Type Assertions]
- Prefer [Type Guards] over [Type Assertions]
- Prefer the `as`-syntax for [Type Assertions] over the angle-bracket syntax
- Use the [Nullish coalescing operator]
- Prefer [Union Types], [Lookup Types], [Mapped Types] and [Const Assertions] over [Enums]

[any]: https://www.typescriptlang.org/docs/handbook/basic-types.html#any
[arrow functions]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
[async/await]: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await
[classes]: https://www.typescriptlang.org/docs/handbook/classes.html
[const assertions]: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-4.html#const-assertions
[decorators]: https://www.typescriptlang.org/docs/handbook/decorators.html
[enums]: https://www.typescriptlang.org/docs/handbook/enums.html
[eslint]: https://eslint.org/
[extending interfaces]: https://www.typescriptlang.org/docs/handbook/interfaces.html#extending-interfaces
[functions]: https://www.typescriptlang.org/docs/handbook/functions.html
[generic constraints]: https://www.typescriptlang.org/docs/handbook/generics.html#generic-constraints
[interfaces]: https://www.typescriptlang.org/docs/handbook/interfaces.html
[lookup types]: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-1.html#keyof-and-lookup-types
[mapped types]: https://www.typescriptlang.org/docs/handbook/advanced-types.html#mapped-types
[mixins]: https://www.typescriptlang.org/docs/handbook/mixins.html
[non-null assertion operator]: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-0.html#non-null-assertion-operator
[nullish coalescing operator]: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html#nullish-coalescing
[optional properties]: https://www.typescriptlang.org/docs/handbook/interfaces.html#optional-properties
[overloading functions]: https://www.typescriptlang.org/docs/handbook/functions.html#overloads
[prettier]: https://prettier.io/
[readonly]: https://www.typescriptlang.org/docs/handbook/interfaces.html#readonly-properties
[strict mode]: https://www.typescriptlang.org/docs/handbook/compiler-options.html
[type aliases]: https://www.typescriptlang.org/docs/handbook/advanced-types.html#type-aliases
[type assertions]: https://www.typescriptlang.org/docs/handbook/basic-types.html#type-assertions
[type guards]: https://www.typescriptlang.org/docs/handbook/advanced-types.html#type-guards-and-differentiating-types
[union types]: https://www.typescriptlang.org/docs/handbook/advanced-types.html#union-types

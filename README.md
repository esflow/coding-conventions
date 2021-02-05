
### Naming conventions

| What                   | How         | Example                                    | Note                                                          |
| ---------------------- | ----------- | ------------------------------------------ | ------------------------------------------------------------- |
| Files & Folders        | hyphen-case | `/radio-button/radio-button.tsx`           |                                                               |
| Variables              | camelCase   | `const exampleVar = 1`                     |
| Functions              | camelCase   | `function exampleFunction() { }`           | Prefer `const` and arrows: `const exampleFunction = () => {}` |
| Classes                | PascalCase  | `class ExampleClass { method() { } }`      |
| Interfaces             | PascalCase  | `interface ExampleInterface { member: T }` |
| Enums and enum members | PascalCase  | `enum Color { Red, Green, Blue }`          |
| Array types            | `[]`        | `items: string[]`                          | Don't use `Array<string>`                                     |
| i18n                   | TITLE_CASE  | `clubs.CREATE_FORM.TITLE`                  | `clubs` in this case is namespace                             |

We don't use Hungarian notation, we don't use `I` prefixes for interfaces, or `E` for enums.

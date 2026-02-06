# Titanium Language Support

A VS Code extension providing syntax highlighting for the Titanium programming language.

## Features

- **Syntax Highlighting**: Full support for Titanium language syntax including:
  - Keywords: `module`, `import`, `var`, `const`, `function`, `if`, `else`, `for`, `while`, `return`, etc.
  - Type keywords: `is`, `as`, `extends`, `to`
  - Types: `Int`, `UInt`, `Float`, `Bool`, and their sized variants (`Int8`, `Int32`, `Float64`, etc.)
  - Comments: Single-line (`//`), multi-line (`/* */`), and documentation comments (`///`, `/** */`)
  - String and numeric literals
  - Operators: arithmetic, comparison, logical, bitwise, assignment
  - Function declarations and calls
  - Classes and object names (capitalized identifiers)

- **Bracket Matching**: Automatic bracket pair highlighting and matching
- **Auto-closing Pairs**: Automatic closing of brackets and quotes

## Supported File Extensions

- `.ti`
- `.titan`
- `.titanium`

## Language Features Supported

### Keywords

- **Declaration**: `var`, `const`, `function`, `object`, `alias`, `import`, `module`
- **Access Modifiers**: `public`, `private`, `static`
- **Control Flow**: `if`, `else`, `for`, `while`, `return`, `break`, `continue`, `switch`, `case`, `default`
- **Type Keywords**: `is`, `as`, `extends`, `to`
- **Logical**: `and`, `or`, `not`
- **Constants**: `true`, `false`, `null`

### Types

Primitive types:

- Integer: `Int`, `UInt`, and sized variants (`Int8`, `Int16`, `Int32`, `Int64`, `UInt8`, `UInt16`, `UInt32`, `UInt64`)
- Float: `Float`, and sized variants (`Float8`, `Float16`, `Float32`, `Float64`)
- Other: `Bool`, `String`, `Array`, `Map`, `Void`

### Comments

- Single-line: `// comment`
- Multi-line: `/* comment */`
- Documentation: `/** doc */` and `/// doc`

### Operators

- Arithmetic: `+`, `-`, `*`, `/`, `%`
- Comparison: `==`, `!=`, `<`, `>`, `<=`, `>=`
- Logical: `&&`, `||`, `!`
- Bitwise: `&`, `|`, `^`, `~`, `<<`, `>>`
- Assignment: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `&=`, `|=`, `^=`
- Special: `->`, `::`, `.`, `,`

## Installation

Install from the VS Code Extension Marketplace by searching for "Titanium Language Support"

## Project Structure

```txt
titanium-extension/
├── package.json                          # Extension manifest
├── language-configuration.json           # Language configuration
├── syntaxes/
│   └── titanium.tmLanguage.json         # TextMate grammar for syntax highlighting
└── README.md                             # This file
```

## License

ISC

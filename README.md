# [WIP] JLox Compiler - Crafting Interpreters

JLox is an implementation of the Lox programming language, as described in the book ["Crafting Interpreters"](https://craftinginterpreters.com) by Robert Nystrom. This project provides a fully functional compiler for the Lox language, allowing you to write and execute Lox programs.

## Features

- **Lexical Analysis:** JLox uses a scanner to tokenize the input source code, breaking it down into meaningful chunks (tokens).

- **Syntax Parsing:** The tokens are parsed into an abstract syntax tree (AST) using recursive descent parsing, ensuring correct grammatical structure.

- **Semantic Analysis:** JLox performs semantic analysis to identify and report various kinds of errors in the source code.

- **Interpreter:** The compiler interprets the AST and executes the Lox program, providing runtime results.

## Example (when completed)

```lox
// Hello, World in Lox
print "Hello, World!";
```

## Contributing

1. Fork the repository and create your branch:
   ```sh
   git checkout -b feature/my-feature
   ```

2. Commit your changes and push to the branch:
   ```sh
   git commit -m "Added feature"
   git push origin feature/my-feature
   ```

3. Create a pull request, describing your changes in detail.

---
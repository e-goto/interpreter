# Interpreter

Interpreter written in Go for a language with a C-like syntax.

This interpreter parses and evaluates a language called Monkey. Monkey has the following features:
- C-like syntax
- variable bindings
- integers and booleans
- arithmetic expressions
- build-in functions
- first-class and higher-order functions
- closures
- a string data structure
- an array data structure
- a hash data structure

Example syntax:
```
let age = 1;
let name = "Monkey";
let myArray = [1, 2, 3, 4, 5];
let dict = {"name": "egoto", "cactus": "prickly"}
let add = fn(a, b) { a + b;};
```

Progress:
- [ ] lexer
- [ ] parser
- [ ] abstranct syntax tree
- [ ] object system
- [ ] evaluator
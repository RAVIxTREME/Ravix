# Ravix

A statically typed, interpreted programming language building in C++.

```rx
//example 
int age = 18;

if (age >= 18) {
    print("Adult hai tu!");
} else {
    print("Chhota hai abhi!");
}
```

## About

Ravix is a custom programming language with a C-style syntax, designing and implementing as a final-year diploma project (Computer Science Engineering). The goal was to understand how programming languages actually work under the hood — from raw source code to execution — by building one from the ground up rather than just using existing ones.

## Features

- Static typing (`int`, `float`, `string`, `bool`)
- C-style syntax with curly braces and semicolons
- Conditionals (`if` / `else`)
- Loops (`while`)
- Functions with parameters and return values
- Custom file extension: `.rx`
- Syntax highlighting support in VS Code

## Temporary Example

```rx
int add(int a, int b) {
    return a + b;
}

int result = add(5, 3);
print(result);

int i = 0;
while (i < 5) {
    print(i);
    i = i + 1;
}
```

## Getting Started

### Prerequisites
- A C++17 compatible compiler (e.g. g++)

### Build
```bash
//it will fill okay :)
```

### Run a Ravix program
```bash
./ravix run examples/hello.rx
```

## Why Ravix?

Most CS students use programming languages without ever seeing how they're built. This project was an attempt to go one level deeper — designing a syntax, writing a lexer to tokenize source code, building a parser to construct an abstract syntax tree, and writing a tree-walking interpreter to execute it.

It started as a learning exercise inspired by *Crafting Interpreters* by Robert Nystrom, and grew into a complete language with its own file extension and editor support.

## Roadmap

- [ ] Add `for` loops
- [ ] Add arrays/lists
- [ ] Add string manipulation functions
- [ ] Improve error messages with better diagnostics
- [ ] Package manager for Ravix modules

## Author

**Ravi**
Diploma in Computer Science Engineering
DY Patil Polytechnic, Akurdi, Pune

## License

MIT License — feel free to fork, learn from, and build on this project.

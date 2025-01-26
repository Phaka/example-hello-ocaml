# Hello World in OCaml

A minimal "Hello, World!" implementation in OCaml. OCaml is a functional programming language that also supports imperative and object-oriented styles. It features strong static typing, type inference, and pattern matching.

## Installation

### macOS
Using Homebrew:
```bash
brew install ocaml
```

### Linux
Ubuntu/Debian:
```bash
sudo apt-get update
sudo apt-get install ocaml
```

Fedora/RHEL:
```bash
sudo dnf install ocaml
```

### Windows
Install OCaml using the OCaml for Windows installer available from the official website, or use WSL (Windows Subsystem for Linux) and follow the Linux installation instructions.

## Running

OCaml provides several ways to run programs:

Direct interpretation:
```bash
ocaml main.ml
```

Compile and run:
```bash
# Compile to native code
ocamlopt -o hello main.ml

# Run the executable
./hello
```

## Code Explanation

The program demonstrates OCaml's simplicity in basic operations while hinting at its sophisticated type system. OCaml uses `print_endline` for printing strings with a newline. The function has type `string -> unit`, meaning it takes a string argument and returns `unit` (similar to `void` in other languages). OCaml comments are enclosed in `(* *)` pairs, which can be nested.

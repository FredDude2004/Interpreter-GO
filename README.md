

# Interpreter from Scratch

# TODO Make this not crap


## Overview

This project is a fully functional interpreter built from the ground up in Go. It implements 
a programming language with a lexer, parser, an abstract syntax tree (AST), and an evaluator. 
The goal of this project is to develop a deep understanding of how interpreters work, covering 
key concepts such as lexical analysis, tokenization, parsing, and execution of code.

## Features

Lexer: Tokenizes input source code into meaningful components.

Parser: Constructs an Abstract Syntax Tree (AST) from tokenized input.

Evaluator: Executes parsed expressions and statements.

Environment Handling: Supports variable bindings and scope management.

Operators and Expressions: Arithmetic, boolean logic, and conditionals.

Functions and Closures: First-class functions with support for closures.

## Technical Details

Language: Go (Golang)

REPL: Interactive Read-Eval-Print Loop for testing code live.

Memory Management: Uses Go’s garbage collection for automatic memory handling.

Design Choices: Recursive descent parsing for clarity and maintainability.

Why This Matters

Writing an interpreter from scratch builds a strong foundation in language design, compiler theory, and testable software design. This project showcases:

Proficiency in Go: Understanding and implementing key language features.

Lexical Analysis & Parsing Techniques: Tokenizing and structuring input code.

Functional Programming Concepts: Handling first-class functions and closures.

Test-Driven Development (TDD): Writing modular and testable components to ensure correctness and maintainability.

Ability to Work with Complex Data Structures & Algorithms: Implementing an AST, recursive parsing, and evaluation logic.

Installation & Usage

# Clone the repository
git clone https://github.com/yourusername/interpreter.git
cd interpreter

# Build and run the interpreter
go run main.go

# Start the interactive REPL
./interpreter
>> let x = 5;
>> x + 10;
15

Future Enhancements

Extending the Language: Adding more built-in functions and data types.

Optimizations: Improving performance and memory efficiency.

Bytecode Compilation: Implementing a VM-based execution model.

Contact

For any questions or collaboration opportunities, feel free to reach out via GitHub issues or email. Interpreter-GO

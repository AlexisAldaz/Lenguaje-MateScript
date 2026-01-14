# MateScript

A custom interpreted language built in Python, specialized for linear algebra and floating-point arithmetic.

## Overview
MateScript is a Domain-Specific Language (DSL) designed to simplify matrix manipulations and numerical computations. It features a custom-built lexer, parser, and evaluator that handles high-precision floating-point numbers and matrix structures natively.

## Key Features
* **Data Types:** Restricted to Float and Matrix types for optimized numerical focus.
* **Matrix Operations:** Native support for matrix addition, subtraction, multiplication, and transposition.
* **Arithmetic:** Full support for standard floating-point operations.
* **Architecture:** Built using a Recursive Descent Parser and a tree-walk interpreter.

## Technical Details
The project is structured into three main components:
1.  **Lexer:** Converts source code into a stream of tokens (Numbers, Brackets, Operators).
2.  **Parser:** Organizes tokens into an Abstract Syntax Tree (AST) representing the mathematical structure.
3.  **Evaluator:** Traverses the AST to perform calculations and return results.

## Technologies
* Python 
* Numpy
* Pandas

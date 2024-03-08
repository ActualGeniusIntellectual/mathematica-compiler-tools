# Rustica Documentation

## Overview

This document provides comprehensive documentation for Rustica, a Rust-based interpreter for a subset of the Mathematica language. The interpreter is designed to handle basic arithmetic operations, derivatives of polynomials, and a selection of Mathematica's fundamental features.

## Features

### Arithmetic Operations

- **Supported Operators**: Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`), and Power (`^`).
- **Order of Operations**: The interpreter follows the standard mathematical precedence and associativity rules, with parentheses (`(`, `)`) used to alter these rules.

### Polynomial Operations

- **Polynomial Definition**: Users can define polynomial expressions.
- **Derivative Computation**: The interpreter can compute the first and higher-order derivatives of polynomials.

### Basic Functions

- **`Sum` Function**: Summation of a sequence or series.
- **`Product` Function**: Product of a sequence or series.
- **`Factorial` Function**: Computes the factorial of a number.

### List/Array Operations

- **List Definitions**: Ability to create and manipulate lists of numbers.
- **`Map` Function**: Applies a given function to each element of a list.
- **`Range` Function**: Generates a list of numbers in a specified range.

### Control Structures

- **`For` Loops**: Basic looping functionality with a specified range and step.
- **`If` Statements**: Conditional logic implementation.

### Variable Assignments

- **Variable Handling**: Users can assign and reassign values to variables.

### Basic Mathematical Functions

- **Trigonometric Functions**: `Sin`, `Cos`, `Tan`.
- **Exponential and Logarithmic Functions**: `Exp`, `Log`.

### Input and Output

- **Output**: The interpreter can output results to the console.
- **Input**: Basic input handling for scripting (no interactive input in the current version).

### Error Handling

- **Error Messages**: Basic error messages for syntax errors and mathematical exceptions (e.g., division by zero).

## Limitations

- **Symbolic Computation**: Not supported in the current version.
- **Graphical Capabilities**: No support for graphical outputs.
- **Advanced Mathematical Functions**: Limited to the basic functions listed above.
- **Complex Numbers**: Handling of complex numbers is not implemented.

## Future Scope

- **Expansion of Mathematical Functions**: Including more complex functions and symbolic computation.
- **Graphical Support**: Adding the ability to render graphical representations of functions.
- **Complex Number Support**: Introducing support for complex number arithmetic and functions.
- **Performance Optimization**: Continuous improvements in the efficiency and speed of the interpreter.

## Example Usage

(TODO: Provide examples of how to use the interpreter with various types of Mathematica syntax covered in this implementation.)

## Contributing

We welcome contributions to extend and improve the Rustica. Please refer to the `CONTRIBUTING.md` file for guidelines on contributing to this project.


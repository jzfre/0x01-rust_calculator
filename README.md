# Rust Calculator

A command-line calculator built in Rust that evaluates mathematical expressions.

## Features

- Evaluates basic arithmetic expressions (+, -, *, /)
- Handles parentheses for grouping
- Follows standard operator precedence rules
- Provides clear error messages for invalid input

## Usage

```bash
# Run directly with an expression
cargo run -- "5 + 3 * 2"

# Or build and run the binary
cargo build --release
./target/release/calc "12/2*3"

# Interactive mode (no arguments)
cargo run

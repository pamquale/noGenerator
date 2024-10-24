# Number Generator... Without Random Number Generator???

Sounds wierd and interesting. This Rust program generate a number based on deterministic transformations,instead of traditional random number generation techniques.

## Overview

The program takes an initial input (in this case, a vector containing a space character), processes it to extract digits, and performs calculations to generate a final number. The final result is constrained to be non-zero and falls within a specific range.

## Features

- Generates a number based on deterministic inputs.
- Utilizes mathematical constants π (Pi) and φ (Phi) in calculations.
- Ensures the result is non-zero and constrained to be within the range of 0 to 99.

## How It Works

1. The program converts the input to a string and filters out any characters that are not digits or are zero.
2. It calculates the product of the remaining digits.
3. The product is then multiplied by π and φ.
4. The result is taken modulo 100.
5. If the result is zero, it replaces it with a non-zero value (e.g., 1).

## Requirements

- Rust (latest stable version)

## Usage

To run the program, follow these steps:

1. Clone the repository or copy the code into a new Rust project.
2. Run the following command in the project directory:

   ```bash
   cargo run

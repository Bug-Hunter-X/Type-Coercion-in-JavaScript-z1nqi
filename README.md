# Type Coercion Bug in JavaScript

This repository demonstrates a common type coercion issue in JavaScript. The `foo` function is intended to add two numbers but produces unexpected results when provided with a number and a string.

## Bug
The `bug.js` file contains the buggy code.  JavaScript's loose typing allows the addition operator (+) to perform string concatenation when one of the operands is a string.

## Solution
The `bugSolution.js` file offers a solution by explicitly converting the inputs to numbers before performing the addition. This prevents unexpected string concatenation.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` in a JavaScript environment.
3. Run the code. You'll see the unexpected output: `12`.
4. Open `bugSolution.js`. You'll see how type coercion is avoided.
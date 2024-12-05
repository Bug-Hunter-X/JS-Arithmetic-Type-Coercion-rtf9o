# Unexpected Type Coercion in JavaScript Arithmetic

This example demonstrates a common issue in JavaScript related to type coercion in arithmetic operations.  Due to JavaScript's dynamic typing, if you perform arithmetic operations with a mixture of numbers and strings, JavaScript will coerce the numbers to strings and perform string concatenation instead of numerical addition.

The `bug.js` file shows the problem. The `bugSolution.js` file offers a solution using explicit type checking or conversion.

## How to Reproduce

1.  Clone this repository.
2.  Open `bug.js`.
3.  Run the code in a JavaScript environment (browser console, Node.js).
4.  Observe the unexpected output.

## Solution

Refer to `bugSolution.js` for a corrected implementation that addresses the type coercion issue.
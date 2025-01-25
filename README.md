# JavaScript Loose Typing Bug

This repository demonstrates a common JavaScript bug stemming from its loose typing system.  The `foo` function intends to add two numbers but unexpectedly concatenates them when a string is passed as an argument.

## Bug Description
The `bug.js` file contains a function that should add two numbers. However, due to JavaScript's implicit type coercion, passing a number and a string results in string concatenation rather than numerical addition.

## Solution
The `bugSolution.js` file shows a corrected version of the function with explicit type checking to ensure that both inputs are numbers before attempting addition.  This helps avoid unexpected behavior.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment.
3. Observe the unexpected output.
4. Open `bugSolution.js` to see the corrected implementation.
# JavaScript Null Value Handling in Arithmetic Operations

This repository demonstrates a common error in JavaScript: improper handling of null values in arithmetic operations.

## The Bug
The `foo` function in `bug.js` attempts to add two numbers.  However, it doesn't explicitly check for null values, leading to unexpected behavior when one or both inputs are null.  In those cases, a `TypeError` might be thrown or unexpected results returned.

## The Solution
The `bugSolution.js` file provides a corrected version of the `foo` function.  It explicitly checks for null values before performing addition, returning null if either input is null.

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment (like a browser's console or Node.js).
3. Run the code and observe the differences in output.

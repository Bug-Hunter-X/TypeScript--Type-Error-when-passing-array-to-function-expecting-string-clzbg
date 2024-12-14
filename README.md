# TypeScript Type Error: Passing Array to String Function

This repository demonstrates a common TypeScript error: passing an array to a function that expects a single string argument.  The `bug.ts` file shows the erroneous code, while `bugSolution.ts` provides a corrected version.

## Problem

The `greeter` function is designed to take a single string and return a greeting. However, the code attempts to pass an array of strings to it, resulting in a type error.

## Solution

The solution involves iterating through the array and calling the `greeter` function for each string element.  This ensures that the type system is satisfied and prevents the error.

## How to run

1. Clone the repository
2. Navigate to the project directory
3. Compile and run the code using a TypeScript compiler: `tsc bug.ts && node bug.js` and `tsc bugSolution.ts && node bugSolution.js`
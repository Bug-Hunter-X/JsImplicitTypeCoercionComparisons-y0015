# Implicit Type Coercion in JavaScript Comparisons
This repository demonstrates a common error in JavaScript: implicit type coercion in comparisons.  The strict equality operator (===) should be used to prevent unexpected behavior when comparing values of different types.  The `bug.js` file contains the problematic code, and `bugSolution.js` provides a corrected version.

## Problem
In JavaScript, loose comparison (==) can lead to unexpected results due to implicit type coercion.  For example, `0 == false` evaluates to `true`, even though they are of different types.  The strict equality operator (===) performs a comparison without type coercion, providing more predictable behavior.

## Solution
Always use the strict equality operator (===) when comparing values in JavaScript to ensure type safety and avoid unexpected results.
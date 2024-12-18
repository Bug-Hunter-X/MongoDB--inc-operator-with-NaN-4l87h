# MongoDB $inc Operator with NaN

This example demonstrates an uncommon error that can occur when using the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numeric field by a specified value. However, if you provide a non-numeric value such as `NaN` (Not a Number), it will not work as expected and may lead to unexpected behavior.

## Bug
The `bug.js` file shows incorrect usage of `$inc` with `NaN`.

## Solution
The `bugSolution.js` file demonstrates the correct usage of `$inc` with a numeric value. Ensure that you are providing a valid number to the `$inc` operator.

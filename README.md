# MongoDB $inc Operator Bug

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numeric field by a specified value.  However, if the value provided is not a number, it will lead to an error.

## Bug

The `bug.js` file demonstrates the incorrect usage of the `$inc` operator, where a string is passed as the value. This causes MongoDB to throw an error. 

## Solution

The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator with a numeric value, correctly incrementing the field.
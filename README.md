# MongoDB $inc Operator Error with String Value
This repository demonstrates an uncommon error in MongoDB when using the $inc operator with a string value instead of a numeric value. The $inc operator is used to increment a numeric field in a document.  If you provide a string value to $inc, it won't increment the value, leading to unexpected behavior. This example shows the incorrect usage and provides a corrected version.

## Bug
The `bug.js` file contains the erroneous code that uses a string with the `$inc` operator.

## Solution
The `bugSolution.js` file shows the corrected code. The solution is to ensure that you always provide a number to the `$inc` operator to avoid errors.
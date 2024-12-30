# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, if a string is provided as the increment value, MongoDB will not perform the intended numerical increment and may throw an error or produce unexpected results.

The `bug.js` file shows the erroneous code. The `bugSolution.js` file provides the corrected code.

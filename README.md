# Incorrect Use of $inc Operator in MongoDB

This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation.  The `$inc` operator is used to increment a numerical field by a specified value.  Attempting to increment with a non-numeric value will result in an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  The code attempts to increment the `count` field by the string value 'abc', which is not a valid numerical value.

## Solution
The solution involves providing a valid numerical value to the `$inc` operator. The example below demonstrates the correct usage.

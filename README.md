# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a given value.  However, the example code tries to increment a field by a string value, which results in an error.

## Bug
The bug lies in passing a string ("1") to the `$inc` operator instead of a number (1).

## Solution
The solution involves correcting the input value for the `$inc` operator to a number, ensuring the field being incremented is of a numeric type, and handling potential errors.

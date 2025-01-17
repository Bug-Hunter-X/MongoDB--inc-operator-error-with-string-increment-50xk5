# MongoDB $inc Operator Error with String Increment

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error occurs when attempting to increment a field by a string value instead of a numerical value.  This can lead to unexpected results or errors.

## Bug
The bug lies in the incorrect usage of the `$inc` operator. The code attempts to increment the 'field' by the string '1' instead of the number 1. 

## Solution
The solution corrects the usage of the `$inc` operator to use a numerical value for the increment.  This ensures the correct behavior of the update query.
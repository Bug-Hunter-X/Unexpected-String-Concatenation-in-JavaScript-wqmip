# Unexpected String Concatenation in JavaScript

This repository demonstrates a common error in JavaScript: unexpected string concatenation due to JavaScript's loose typing. When performing arithmetic operations, ensure that both operands are of a numeric type to avoid this issue.

## Bug
The `foo` function attempts to add a number and a string.  JavaScript interprets this as string concatenation, resulting in '12' instead of 3.

## Solution
The solution explicitly converts the string to a number before performing the addition. This ensures the operation is performed numerically.
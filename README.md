# JavaScript Division by Zero Bug

This repository demonstrates a common error in JavaScript: division by zero. The `myFunc` function attempts to divide two numbers, but it fails to handle the case where either number is zero, leading to a runtime error. The solution demonstrates how to correctly handle this scenario.

## Bug

The original `myFunc` function incorrectly handles zero values. It returns 0 when either `a` or `b` is zero. This is incorrect as the correct behaviour is to check explicitly for division by zero.

## Solution

The solution introduces error handling to check if the divisor is zero, preventing the division by zero error. It returns `Infinity` when the divisor is zero.
# Uncommon ZeroDivisionError Behavior in Python
This repository demonstrates an uncommon behavior of the ZeroDivisionError exception in Python.  The `function_with_uncommon_error` function does not raise a ZeroDivisionError when both input arguments are zero, leading to unexpected behavior.

## Problem
The function is supposed to handle division by zero gracefully, but it fails to do so when both `a` and `b` are 0. Instead of raising a ZeroDivisionError, it returns 0.

## Solution
The solution involves explicitly checking for the case where both `a` and `b` are zero and raising a ZeroDivisionError or handling it appropriately.
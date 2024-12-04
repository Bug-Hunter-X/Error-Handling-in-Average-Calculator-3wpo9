# Python Average Calculation Bug

This repository demonstrates a common error in Python when calculating the average of a list of numbers: the function doesn't handle non-numeric elements or an empty list correctly.  The `bug.py` file shows the buggy code, while `bugSolution.py` provides a robust solution.

## Bug Description

The `calculate_average` function fails when it encounters a list containing non-numeric values, such as strings, raising a `TypeError`.  Additionally, it should gracefully handle the case of an empty list to prevent a `ZeroDivisionError`.

## Solution

The solution incorporates input validation to check for non-numeric elements and handles the empty list case, preventing errors and producing a more robust function.
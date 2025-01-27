# Python: Handling ZeroDivisionError in Average Calculation

This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating an average of an empty list.  The `bug.py` file shows the flawed code, while `bugSolution.py` presents a corrected version.

## Bug Description

The original `calculate_average` function does not check for an empty input list, leading to a `ZeroDivisionError` when `len(numbers)` is zero. 

## Solution

The improved function in `bugSolution.py` adds a check for an empty list, returning 0 in that case. This handles the edge case gracefully, preventing the error.

## How to run

1. Clone the repository.
2. Run the buggy code: `python bug.py` (this will throw an error)
3. Run the corrected code: `python bugSolution.py` (this will execute without errors)
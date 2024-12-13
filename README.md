# Groovy NullPointerException in Arithmetic Operations

This repository demonstrates a common error in Groovy related to handling null values in arithmetic expressions.  The `calculate` function attempts to add two numbers, but doesn't correctly handle the scenario where one or both inputs are null.  This can lead to unexpected behavior or `NullPointerExceptions`.

The `bug.groovy` file contains the buggy code.  The solution, which employs more robust null handling, is found in `bugSolution.groovy`.
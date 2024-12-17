# Unexpected Null Behavior in Addition Function

This repository demonstrates a common JavaScript error involving unexpected null behavior in an addition function. The function `foo` is intended to add two numbers, but it returns `null` if either input is `null`. This might not be the desired behavior in all cases.

## Bug

The `bug.js` file contains the faulty function.  The issue is that the function immediately returns null if either input is null. This means it doesn't handle cases where one input is a number and the other is null.

## Solution

The `bugSolution.js` file provides a corrected version of the function. It handles null values by treating them as 0, resulting in a more robust and predictable behavior.  This solution prevents unexpected `null` results and provides a more robust handling of potentially null inputs.
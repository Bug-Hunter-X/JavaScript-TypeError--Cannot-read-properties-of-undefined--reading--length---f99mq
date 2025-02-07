# JavaScript Bug: Handling Null and Undefined

This repository demonstrates a common JavaScript error: a `TypeError` thrown when attempting to access the `length` property of an undefined value.

The `bug.js` file contains the faulty code. The `bugSolution.js` provides the corrected version.

## Bug Description

The function `foo` checks if a value is `null`. If it is, it returns 0; otherwise, it attempts to return the length of the value. However, if the input is `undefined`, accessing `x.length` will throw an error.

## Solution

The solution involves checking for both `null` and `undefined` before accessing `x.length`.
# Java Off-by-One ArrayIndexOutOfBoundsException

This repository demonstrates a common off-by-one error in Java that leads to an `ArrayIndexOutOfBoundsException`.  The error occurs when iterating over an array and the loop condition is incorrect, causing an attempt to access an index beyond the array's bounds.

## Bug Description:

The `BuggyArray.java` file contains a `for` loop that iterates one element past the end of an array. This results in an `ArrayIndexOutOfBoundsException` during runtime.

## Solution:

The `FixedArray.java` file provides the corrected code with the appropriate loop condition (`i < array.length`).
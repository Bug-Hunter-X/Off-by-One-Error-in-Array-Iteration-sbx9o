# Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java code that occurs when iterating over arrays.  The error results in an `ArrayIndexOutOfBoundsException`. The solution shows the corrected code and explains how to prevent this type of error.

## Bug Description

The bug lies in the first `for` loop of the provided Java code. When accessing array elements, the index starts at 0 and ends at array.length - 1. In the buggy code, i <= array.length tries to access an element that does not exist, causing an exception.

## Solution

The solution changes the loop condition to i < array.length to ensure that the loop correctly iterates through all valid array indices.

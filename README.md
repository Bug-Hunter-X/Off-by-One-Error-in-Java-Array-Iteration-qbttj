# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java that can lead to an `ArrayIndexOutOfBoundsException`. The bug involves iterating over an array using a loop that goes beyond the valid index range.  The solution shows how to correct the loop to avoid the error. 

## Bug

The provided `bug.java` file contains the erroneous code with the off-by-one error.  The loop condition `i <= arr.length` causes an attempt to access an index that is outside the bounds of the array, resulting in an exception.

## Solution

The `bugSolution.java` file provides a corrected version that addresses the off-by-one error. The loop condition is changed to `i < arr.length` to iterate correctly within the valid index range of the array.
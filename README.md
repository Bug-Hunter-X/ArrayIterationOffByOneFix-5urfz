# Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs because the loop condition `i <= arr.length` causes an attempt to access an element beyond the array's bounds.  The solution shows the correct way to iterate using `i < arr.length`.
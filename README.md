# Implicit Expansion Error in MATLAB
This repository demonstrates a common error related to implicit expansion in MATLAB. The function `myFunction` attempts to add two arrays with incompatible dimensions, leading to an error. The solution shows how to correctly handle dimensions to prevent the error.

## Bug Description
The bug occurs in the `myFunction` function. It tries to add two arrays (`a` and `b`) with incompatible dimensions, which leads to an implicit expansion error. This error can often be overlooked and is especially difficult to debug when dealing with large or complex arrays.
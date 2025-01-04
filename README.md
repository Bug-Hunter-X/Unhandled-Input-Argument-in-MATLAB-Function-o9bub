# Unhandled Input Argument in MATLAB Function

This repository demonstrates a common error in MATLAB: calling a function without providing a required input argument. The function `myFunction` is defined to take an input but it's called without an argument in the example, leading to an error. The solution shows how to correct this by providing the necessary input.

## Bug
The original MATLAB code in `bug.m` contains a function that fails to handle the case where no input is provided. When you run the script it throws an error because the input variable is undefined inside the function.

## Solution
The solution code in `bugSolution.m` is a corrected version that handles the case where an input is missing. This is achieved by adding a check to see if the input argument exists, thereby handling this edge case.

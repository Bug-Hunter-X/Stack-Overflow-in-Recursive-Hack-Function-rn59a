# Stack Overflow in Recursive Hack Function

This repository demonstrates a stack overflow error in a recursive Hack function. The `foo` function calculates the factorial of a number using recursion.  For larger inputs, the recursion depth exceeds Hack's limit, resulting in a stack overflow.

The `bug.hack` file contains the buggy code.  The `bugSolution.hack` file offers a solution using iteration to avoid the stack overflow.

## How to reproduce

1. Clone this repository.
2. Compile and run `bug.hack` with a relatively large input (e.g., `hhc bug.hack` and then run the compiled program).
3. Observe the stack overflow error.
4. Compile and run `bugSolution.hack`. Note that the iterative approach correctly computes the factorial without encountering a stack overflow.
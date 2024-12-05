# Tcl: Division by Zero Bug
This repository demonstrates a common error in Tcl programming: division by zero. The `badproc` procedure fails to handle the case where the first argument is 0, resulting in an error.  The solution shows how to handle this case gracefully.

## Bug
The `bug.tcl` file contains the buggy `badproc` procedure. When called with 0 as the first argument, it will throw a runtime error.

## Solution
The `bugSolution.tcl` file shows a corrected version of the procedure, which handles the division by zero case properly by using an `if` condition to check for the divisor being zero.

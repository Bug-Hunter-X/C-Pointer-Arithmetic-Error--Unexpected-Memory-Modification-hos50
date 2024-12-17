# C Pointer Arithmetic Error
This repository demonstrates a common C error related to pointer arithmetic and unexpected memory modification. The `bug.c` file contains the erroneous code, while `bugSolution.c` provides a corrected version.

The error arises from directly modifying the value pointed to by a pointer without properly considering potential memory issues. In this example, the value of 'x' changes unexpectedly.  The solution emphasizes safe pointer usage and avoids potential memory corruption. 

## How to Use
1. Clone this repository.
2. Compile the `bug.c` and `bugSolution.c` files using a C compiler (like GCC).
3. Run the compiled executables and observe the output.

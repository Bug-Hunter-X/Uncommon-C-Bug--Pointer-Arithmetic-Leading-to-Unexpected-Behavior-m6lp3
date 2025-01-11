# Uncommon C Bug: Pointer Arithmetic Leading to Unexpected Behavior

This repository demonstrates a subtle bug related to pointer arithmetic in C.  The code appears simple, but it highlights a potential source of unexpected behavior that can be difficult to track down in larger projects.

## The Bug

The `bug.c` file contains the erroneous code.  This demonstrates how modifying a variable through a pointer can unexpectedly change the variable's value.   This bug can lead to segmentation faults, undefined behavior and unexpected results. It is often overlooked in code that manages memory manually.

## The Solution

The `bugSolution.c` file presents a corrected version of the code.
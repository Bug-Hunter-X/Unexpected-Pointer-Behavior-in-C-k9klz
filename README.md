# Unexpected Pointer Behavior in C

This repository demonstrates a simple C program that exhibits unexpected behavior due to improper pointer usage.  The program aims to highlight a common pitfall for beginners in C programming involving direct pointer manipulation and memory modification.

## The Bug
The `bug.c` file contains a program that initializes an integer variable and then modifies its value indirectly through a pointer. While seemingly straightforward, this can lead to unexpected side effects in larger, more complex programs.

## The Solution
The `bugSolution.c` file presents a corrected version of the program, showcasing good practices for pointer manipulation in C.  It provides a more robust and predictable way to handle pointer assignments and memory management.
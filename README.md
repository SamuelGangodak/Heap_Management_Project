
# Heap Management System





## Overview

This project showcases the implementation of a heap management system utilizing functions for dynamic memory allocation and deallocation. It employs the First-Fit strategy to allocate memory blocks based on the first suitable fit within the heap structure.
## Functions

- `use_heap()` : initializes the heap 
- `allocate_memory()` : finds the first suitable memory block that fits the requested amount of memory and returns the starting address of the block
- `merge()` : helps to merge adjacent free blocks of memory
- `free_memory()` : frees the memory used by the variable
- `return_heap()` : frees all allocated heap memory so that it can be reused later






## Usage

### Compilation

To compile the code run *Makefile*. You can use the following commands based on your operating system:

- For Windows (using mingw32-make) : `mingw32-make all`
- For macOS or Linux (using make): `make all`

### Execution

To execute the code, run the executable file generated during compilation.

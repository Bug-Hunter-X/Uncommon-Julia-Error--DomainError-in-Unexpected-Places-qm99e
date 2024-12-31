# Uncommon Julia Error: DomainError in Unexpected Places

This repository demonstrates an uncommon error in Julia that can be tricky to debug: the `DomainError`.  `DomainError` exceptions are thrown when a function receives an input outside of its defined domain.  While common with functions like `sqrt` and `log`, they can appear unexpectedly in other contexts.

The `bug.jl` file contains a function that exhibits this behavior.  The solution, provided in `bugSolution.jl`, demonstrates how to avoid this type of error.

This example highlights the importance of carefully considering input validation and error handling in Julia, particularly when working with mathematical functions or operations that have domain restrictions.  Unexpected inputs can lead to exceptions that can be hard to track down without understanding the underlying mathematical limitations.
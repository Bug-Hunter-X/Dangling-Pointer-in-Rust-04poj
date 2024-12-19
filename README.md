This repository demonstrates a common error in Rust where a dangling pointer is created by modifying a vector through a raw pointer after the vector has gone out of scope.
The `bug.rs` file contains code that produces this error.
The `bugSolution.rs` file provides a solution using safe Rust techniques to avoid the use of raw pointers when possible.
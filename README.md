# Rust Raw Pointer Vector Modification Bug
This repository demonstrates a potential issue when using raw pointers to modify Rust vectors.  Modifying a vector's elements through a raw pointer after the vector's capacity has been changed may lead to undefined behavior or crashes.  The `bug.rs` file contains the buggy code, while `bugSolution.rs` offers a safer alternative using vector indexing.
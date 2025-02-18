# Mutable Reference Pitfall in Rust

This example demonstrates a subtle but important point about mutable references in Rust. While the code executes without error, it highlights potential issues when dealing with multiple mutable references to the same data.

The `bug.rs` file contains code which is correct.  However, it could be made better with explicit error handling. 

The solution demonstrates improved safety and clarity.

## How to Run

1.  Save the code in `bug.rs` and `bugSolution.rs` files.
2.  Compile and run using `rustc bug.rs && ./bug` and `rustc bugSolution.rs && ./bugSolution`

## License

MIT
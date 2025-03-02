Cargo is rust's build system & package manager

cargo allows you to 
- downloading the library
- building your code

how to create a project with Cargo?
cargo new <project-name>

inside that project, you will get
- Cargo.toml
- src/main.rs

    Cargo.toml (Tom's Obvious, Minimal Language) 
    it's a Cargo's configuration format.
    it contains: packages, dependencies, etc

Compiling & Running
1. Compile
    > cargo build
2. Running
> cargo run

*actually, running "cargo run" already includes compiling before running
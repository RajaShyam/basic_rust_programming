# Basic Rust Programming Examples

This repository contains basic Rust programming examples created while learning Rust. It demonstrates fundamental Rust concepts and the use of Cargo for project management.

## Setup and Environment

The examples were developed using the following environment:

* **Rust Compiler:** rustc 1.81.0 (eeb90cda1 2024-09-04) (Homebrew)
* **Operating System:** macOS (arm64)

To run these examples, you will need to have Rust and Cargo installed on your system. You can install Rust using rustup, the Rust toolchain installer.

## Project Structure

The repository includes the following:

1.  **`command-line-rust`:**
    * A cloned repository from `https://github.com/kyclark/command-line-rust.git`.
    * This repository contains various Rust command-line utility examples, providing a valuable resource for learning practical Rust applications.
2.  **`my_examples`:**
    * A directory created to hold custom Rust examples.
    * This directory demonstrates the process of creating and running Rust programs, both with and without Cargo.
    * **`hello`:**
        * An example project created using `cargo new hello`.
        * This project demonstrates the basic structure of a Cargo project, including `Cargo.toml`, `src/main.rs`, and the `target` directory.
        * It also shows how to run tests using `cargo test` and build and run the project using `cargo run`.
        * Demonstrates the creation of binary applications, and testing them using `cargo test`.
        * Demonstrates the creation of multiple binary files within the one cargo project.

## Workflow Demonstration

The following steps were taken to create and run the examples:

1.  **Cloning the `command-line-rust` repository:**
    * The `command-line-rust` repository was cloned to provide a set of example Rust command-line utilities.
2.  **Creating a custom example directory:**
    * A `my_examples` directory was created to hold custom Rust examples.
3.  **Creating and compiling a simple "Hello, World!" program:**
    * A `hello.rs` file was created with a basic "Hello, World!" program.
    * The program was compiled using `rustc hello.rs` and executed.
4.  **Organizing the project with Cargo:**
    * The project was converted to a cargo project using `cargo new hello`.
    * Demonstrated the use of `cargo run` and `cargo test`.
5.  **Testing and Binary creation:**
    * Demonstrated how to create tests.
    * Demonstrated how to create multiple binaries within a cargo project.

## Usage

To run the examples:

1.  Clone this repository.
2.  Navigate to the `my_examples/hello` directory.
3.  Use `cargo run` to build and run the "Hello, World!" program.
4.  Use `cargo test` to run the tests.

## Notes

* The `target` directory contains the compiled binaries and other build artifacts.
* The `Cargo.lock` file ensures consistent builds across different environments.
* The examples demonstrate the basic workflow of creating, building, and running Rust programs using Cargo.

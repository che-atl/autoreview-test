# KAN-5 — Go Hello World file in hello directory

> Source: [KAN-5](https://che-1.jira-dev.com/browse/KAN-5) (Epic, project "Hi Celia")

## Go Hello World file in hello directory

The objective of this work is to implement a simple Go "Hello World" application within the specified GitHub repository. This provides a basic entry point and verification for the Go environment in the `autoreview-test` project. The implementation will consist of a single Go source file named `hello_world.go` located within a new `hello/` directory to maintain a clean repository structure.

### Done when

* A new directory named `hello/` exists in the root of the repository.
* A file named `hello_world.go` is created inside the `hello/` directory.
* The `hello_world.go` file contains a `package main` declaration at the top.
* The `hello_world.go` file imports the `fmt` package.
* The `hello_world.go` file contains a `main` function that uses `fmt.Println` to output the string "Hello, World!".
* No `go.mod` file is created or modified as part of this task.

### Out of scope

* Initialization of a Go module (`go.mod` file) as per user preference.
* Implementation of unit tests for the hello world function.
* Configuration of CI/CD pipelines for building or testing the Go code.
* Modifications to any existing files in the repository.

### Context

* https://che-1.jira-dev.com/browse/KAN-5
* https://github.com/che-atl/autoreview-test/tree/main

Celia love coding

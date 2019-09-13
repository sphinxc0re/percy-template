# Percy starter template
This is a simple template to get started working with [percy](https://github.com/chinedufn/percy), a modular toolkit for building web apps with Rust.

## Prerequisites
1. Install **Rust** using **rustup**: https://www.rust-lang.org/tools/install
2. Install `cargo-generate`
```shell
cargo install cargo-generate
```
3. Install `cargo-make`
```shell
cargo install cargo-make
```

## Generating a new project
The following command will generate a new project directory with all the files you need and a preinitialized git repo. During the generation, the tool will ask you for a project name. From this it will generate a directory that will contain the project files.
```shell
cargo generate --git https://github.com/sphinxc0re/percy-template
```

## Building
Inside your project directory, run
```shell
cargo make run
```
This will install all the tools needed, build the project and run a really small and fast web server on port 3000: http://localhost:3000/

## Where to go from here
For the actual documentation on how *percy* works, visit: https://chinedufn.github.io/percy/

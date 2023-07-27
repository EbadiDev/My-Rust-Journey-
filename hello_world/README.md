# Cargo

## Creating a new project with Cargo
```markdown
cargo new <name of project>
or for generating .gitignore
cargo new <name of project> --vcs=git
```
## Run or Build With Cargo
If you want to run it use :
```markdown
cargo run
```
To build use :
```markdown
cargo build
```
which binary file will located in target/debug directory.
## Cargo Check
quickly checks your code to make sure it compiles but doesn’t produce an executable
```markdown
cargo check
```

## Inside of Crago.toml
```toml
[package]
name = "hello_cargo"
version = "0.1.0"
edition = "2021"

[dependencies]
#In Rust, packages of code are referred to as crates
```


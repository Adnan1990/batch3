# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`batch3 = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "hello_world"
version = "0.1.0"
authors = ["Muhammad Adnan <muhammad.adnan1990@gmail.com>"]
edition = "2018"

[dependencies]
batch3 = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use batch3;
fn main() {
    println!("Hello, world!");
    islamabad::piaic();
}
```
following will also work:
```
use batch3::islamabad;
fn main() {
    println!("Hello, world!");
    piaic();
}
```

now `cargo run` for results

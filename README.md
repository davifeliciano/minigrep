# minigrep

Small command line interface to search for patterns in text files. This is a
small project implemented in chapter 12 of the book
[The Rust Programming Language](https://doc.rust-lang.org/stable/book).

## Usage

```bash
cargo build --release # build the binary
target/release/minigrep <pattern> <filename> # case sensitive search
IGNORE_CASE=1 target/release/minigrep <pattern> <filename> # case insensitive search
```

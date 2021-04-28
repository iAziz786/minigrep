# minigrep

minigrep is a very simple implementation of grep in Rust. The implementation is a walkthrough of chapter 12 from "The Book".

### Prerequisite

- Rust

### Search

```
cargo run <<search_string>> <<filename>>
```

Search will do a case sensitive search of the `search_string` at `filename` provided.

### Search (case-insensitive)

```
CASE_INSENSITIVE=1 cargo run <<search_string>> <<filename>>
```

This will do a case insensitive search to the `filename`.

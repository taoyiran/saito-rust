# saito-rust

A work-in-progress draft implementation of the saito core in rust

## Documentation

https://saitotech.github.io/saito-rust/saito_rust/index.html

## Dev workflow

1) Fork the repo.
2) clone the repo, checkout main, and create a feature branch.
```
git clone https://github.com/MyGithubAccount/saito-rust.git
git checkout main
git checkout -b some-feature-branch
```
3) Do some coding.
4) Make sure all unit tests pass(add new unit tests to cover any new code).
```
cargo test
```
5) Add rust-style documention/comments to any new code, fix any comments for code which has changed
6) Make sure code compies with rust fmt rules. "cargo fmt --all -- --check" to see changes or "cargo fmt" to apply them to your working directory.
7) git push MyGithubAccount-remote some-feature-branch
8) Open a PR against main branch

### Deps

```
rustup component add rustfmt
```

### Run the node

```
cargo run
```

### Tests

```
cargo test
```

### Code formatting
```
cargo fmt --all -- --check
```
```
cargo fmt
```

### VSCode

Extensions:

- https://github.com/rust-lang/vscode-rust

## Create release

```
cargo build --release
```

## Further steps

Publish certain rust functionalities (as bin) as a npm package

- https://blog.woubuc.be/post/publishing-rust-binary-on-npm
- https://github.com/EverlastingBugstopper/binary-install

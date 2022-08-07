# Rust

## Run `cargo test`

```yaml
- repo: https://github.com/dacci/pre-commit
  rev: main
  hooks:
    - id: cargo-test
      args: ['--all-features']
```

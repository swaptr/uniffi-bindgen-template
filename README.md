# uniffi-bindgen-template
Template for starting a UniFFI bindgen workspace project in Rust.

[User Guide](https://mozilla.github.io/uniffi-rs) | [Code](https://github.com/mozilla/uniffi-rs)

## Usage:
Use `cargo generate` to clone this template.

```bash
cargo generate --git https://github.com/swaptr/uniffi-bindgen-template.git --name my-project
cd my-project
```

### Building
```bash
cargo build --release
```

### Generate bindings
```bash
cargo run -p uniffi-bindgen generate template/src/template.udl --language python
```

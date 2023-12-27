# Rust Template

This is my personal template for creating new Rust projects. Most of this, especially the linter rules, was cannibalized from [Charles Hall's Rust + Nix Quickstart](https://or.computer.surgery/charles/nix-rust-quickstart), so credit is due there.

## Usage

To use:
1. Install [cargo-generate](https://cargo-generate.github.io/cargo-generate/installation.html)
2. Add this to `$CARGO_HOME/cargo-generate.toml`:
```toml
[favorites.siliconself]
git = "https://github.com/SiliconSelf/rust-template"
branch = "main"
```

After doing this, you can generate a new project with
```
cargo generate siliconself
```
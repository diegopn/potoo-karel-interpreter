<h1 align="center">Karel the Robot Interpreter Scaffold</h1>

<p align="center">An initial Rust crate scaffold for future work on Stanford Java Karel.</p>

<p align="center">
  <a href="https://diegopn.github.io/potoo-site/">Website</a> ·
  <a href="https://diegopn.github.io/potoo-site/manual/karel/">Potoo IDE manual</a>
</p>

<p align="center">
  <a href="https://www.rust-lang.org/"><img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"></a>
  <a href="https://doc.rust-lang.org/cargo/"><img alt="Cargo" src="https://img.shields.io/badge/Cargo-DEA584?style=for-the-badge&logo=rust&logoColor=white"></a>
  <img alt="Rust library" src="https://img.shields.io/badge/Rust_library-4A86CF?style=for-the-badge">
</p>

Karel is an educational programming language built around a robot and a grid world. This repository targets the Stanford Java Karel model, a small subset of Java with robot-specific commands. It is a programming language, not a pseudolanguage, and this scaffold does not claim compatibility with the separate Python model or full Java.

This repository is only a starting scaffold. It does not yet parse or execute Karel the Robot source, and no interpreter features are currently implemented. The Rust implementation will be developed here independently from the original language project.

## Status

There is no functional interpreter or usable CLI yet. The binary entry point is a placeholder and does no work. No prebuilt releases have been published, and this repository has no release workflow.

## Original language references

- [Potoo IDE manual](https://diegopn.github.io/potoo-site/manual/karel/)
- [Stanford Karel Reader — Java version](https://compedu.stanford.edu/karel-reader/docs/java/en/)
- [Stanford Karel command reference](https://compedu.stanford.edu/karel-reader/docs/java/en/reference.html)

These references define the compatibility work. This repository will list its supported syntax, runtime behavior, and limitations after implementation begins.

## Development

Run these commands from the repository root:

```sh
cargo fmt --all -- --check
cargo check
cargo test
```

## Project policies

- [Code of conduct](CODE_OF_CONDUCT.md)
- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)
- [GPL-3.0-or-later license](LICENSE)

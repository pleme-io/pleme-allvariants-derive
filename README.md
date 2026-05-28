# pleme-allvariants-derive

Enum-fold: pub const ALL: &'static [Self] = &[Self::A, Self::B, ...] + pub const fn all(). Unit-variant enums only.

[![Build](https://github.com/pleme-io/pleme-allvariants-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-allvariants-derive.svg)](https://crates.io/crates/pleme-allvariants-derive)

## Install

```toml
[dependencies]
pleme-allvariants-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.

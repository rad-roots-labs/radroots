# radroots-sql-wasm-bridge

Wasm SQL bridge primitives for Radroots data layers.

## Goals

- define stable wasm bridge interfaces for SQL exec, query, and export calls
- keep bridge transaction helper behavior deterministic across wasm integrations
- provide a narrow host interop boundary for SQL runtime crates
- expose reusable wasm SQL bridge primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

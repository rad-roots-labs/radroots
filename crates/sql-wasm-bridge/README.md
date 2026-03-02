# radroots-sql-wasm-bridge

Wasm SQL bridge primitives for Radroots data layers.

## Goals

- define stable wasm bridge interfaces for SQL execute, query, export, and transactions
- keep host interop behavior deterministic across wasm integrations
- support a narrow integration boundary for SQL runtime crates
- provide reusable wasm SQL bridge primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

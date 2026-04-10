# radroots_replica_sync

Replica event ingest and synchronization interfaces for Radroots data layers.

## Goals

- define stable interfaces for event ingest, emit, and sync status
- keep ingest and bundle assembly behavior deterministic across targets
- support canonical transfer payloads for replica synchronization flows
- provide reusable synchronization primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

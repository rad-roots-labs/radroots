# radroots-events-indexed

Indexed manifest and checkpoint models for Radroots event archives.

## Goals

- define stable manifest, checkpoint, and shard range models
- keep shard metadata and id-range validation deterministic across targets
- support no_std and std builds with feature-gated serialization and type export
- provide reusable indexed archive primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

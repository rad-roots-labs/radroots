# radroots-nostr-accounts

Nostr protocol account primitives and vault interfaces for the Radroots SDK.

## Goals

- define stable account, manager, store, and vault interfaces
- keep account selection and persistence behavior deterministic across environments
- support pluggable secret vault backends for local and keyring runtimes
- provide reusable account primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

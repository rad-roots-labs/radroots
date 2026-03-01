# radroots-nostr-accounts

Nostr protocol account primitives and vault interfaces for the Radroots SDK.

## Goals

- define stable account model and manager interfaces for Nostr identities
- support pluggable secret vault backends for local and keyring-backed runtimes
- keep account store and selection behavior deterministic across environments
- provide reusable account primitives for higher-level Radroots crates

## License

Licensed under AGPL-3.0. See LICENSE.

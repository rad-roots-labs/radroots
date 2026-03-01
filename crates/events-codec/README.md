# radroots-events-codec

Reference encoders and decoders for Radroots Nostr event payloads.

## Goals

- define deterministic encode and decode behavior for Radroots event data
- enforce stable parsing and validation across supported event forms
- support std and no_std targets with feature-gated serde_json and nostr integration
- provide a reliable codec layer for runtime and wasm bindings

## License

Licensed under AGPL-3.0. See LICENSE.

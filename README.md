# Radroots

A collaborative and composable architecture for signed agricultural trade records.

## Development

Nix is the canonical environment contract for this workspace.

1. Install Nix and enable flakes.
2. Enter the workspace with `nix develop` or `direnv allow`.
3. Run `nix flake check` for pure formatting, workflow linting, guard, and Rust check/test validation.
4. Run `nix run .#contract` for the repo-aware SDK contract lane.

See `docs/nix.md` for first-time setup, shell usage, and the full command map.

This is Free software and is licensed under the AGPL 3.0. See LICENSE.

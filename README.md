# graphban-rules-releases

Signed Graphban rule packs. Each release `pack-v<version>` carries the pack tar and its raw Ed25519 signature (`.tar.sig`), published by the `pack-release` workflow in asc-me/graphban-rules when a person pushes a `pack-v*` tag.

Servers 2026.11.4 and later verify the signature against their built-in trusted key before loading a pack.

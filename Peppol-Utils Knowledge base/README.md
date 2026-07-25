# Peppol-Utils Knowledge base

This directory is the public static distribution channel for generated
Peppol-utils Knowledge Base artifacts.

The stable channel uses:

- `knowledge-base-manifest.json`
- `knowledge-base-manifest.sig`
- versioned `knowledge-base-v<version>.zip` archives
- matching `.sha256` sidecars
- non-sensitive `build-report.json` metadata

Applications must verify the detached Ed25519 signature on the manifest and
the signed archive size and SHA-256 before installing a bundle. Published
versioned archives must not be replaced in place.

## Current stable bundle

- Version: `2026.07.25.2`
- Documents: 75
- Search chunks: 2,955
- Archive SHA-256:
  `fb987d341e3b14c130c5435da57cc4a4badc4d93b3b5bbd7b21147d61f47264e`
- Signing key ID: `kb-ed25519-2026-01`
- Public-key SHA-256:
  `0e7d44722c32c0e09d66c2ba7d73688532038c920d41343379aaca58a6f8e8dd`

Version `2026.07.25.1` was withdrawn before application integration because
Git normalized the signed manifest's Windows line ending. Version
`2026.07.25.2` uses platform-independent LF bytes for signing and publication.

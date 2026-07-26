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

- Version: `2026.07.26.1`
- Documents: 75
- Search chunks: 3,039
- Archive SHA-256:
  `09ff14e0e2f64f82589144937c7adf3159547748388c9043cd8927496d788ae7`
- Signing key ID: `kb-ed25519-2026-01`
- Public-key SHA-256:
  `0e7d44722c32c0e09d66c2ba7d73688532038c920d41343379aaca58a6f8e8dd`

Version `2026.07.25.1` was withdrawn before application integration because
Git normalized the signed manifest's Windows line ending. Version
`2026.07.25.2` uses platform-independent LF bytes for signing and publication.

Version `2026.07.26.1` adds structure-aware PDF extraction, structured glossary
definitions, current-version preference, retrieval diversity, and a mandatory
15-question publication quality gate.

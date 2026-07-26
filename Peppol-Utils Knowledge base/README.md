# Peppol-Utils Knowledge base

This directory is the public static distribution channel for generated
Peppol-utils Knowledge Base artifacts.

The stable channel uses:

- `knowledge-base-manifest.json`
- `knowledge-base-manifest.sig`
- versioned `knowledge-base-v<version>.zip` archives
- matching `.sha256` sidecars
- non-sensitive `build-report.json` metadata
- mandatory retrieval results in `evaluation-report.json`

Applications must verify the detached Ed25519 signature on the manifest and
the signed archive size and SHA-256 before installing a bundle. Published
versioned archives must not be replaced in place.

## Current stable bundle

- Version: `2026.07.26.2`
- Documents: 75
- Search chunks: 3,039
- Archive SHA-256:
  `7d25f12ff486f14819b66c5320005668b664dc91d6fb41b19a5deeefa8b225fc`
- Signing key ID: `kb-ed25519-2026-07`
- Public-key SHA-256:
  `dd47d02f3024e0ebfbd466b96badece0ec0aad8fb5be39c0d8fe64173092cd72`

Version `2026.07.25.1` was withdrawn before application integration because
Git normalized the signed manifest's Windows line ending. Version
`2026.07.25.2` uses platform-independent LF bytes for signing and publication.

Version `2026.07.26.1` adds structure-aware PDF extraction, structured glossary
definitions, current-version preference, retrieval diversity, and a mandatory
15-question publication quality gate.

Version `2026.07.26.2` requires Peppol-utils 0.6.1 and adds document-first
retrieval, coherent neighboring-page expansion, multilingual terminology
improvements, adaptive prompt context, a 16-question publication gate, and the
July 2026 signing-key rotation.

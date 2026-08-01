# Peppol-Utils Knowledge Base distribution

This directory is the signed stable-channel metadata for the generated Peppol-utils Knowledge Base. The current bundle archive is published as a GitHub Release rather than committed to the source branch.

## Current stable bundle

- Version: `2026.08.01.1`
- Bundle schema: `3`
- Minimum application version: Peppol-utils `0.6.0`
- Documents: 75
- Search chunks: 3,039
- Archive size: 4,144,152 bytes
- Archive SHA-256: `573e29863c397754badd47ff1becac9fe467937c8580733ae1f2c6d3411f478f`
- Signing key ID: `kb-ed25519-2026-07`
- Release: [kb-v2026.08.01.1](https://github.com/Duclevn/Peppol-utils-KB/releases/tag/kb-v2026.08.01.1)

The application authenticates the exact bytes of `knowledge-base-manifest.json` with `knowledge-base-manifest.sig`, then verifies the signed archive URL, size, and SHA-256 before installation. The current application requires schema-v3 bundles.

Only the current downloadable bundle is retained. Source documents and Git history remain available for reproducible provenance and citations.

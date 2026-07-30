# Peppol-Utils Knowledge Base distribution

This directory is the signed stable-channel metadata for the generated Peppol-utils Knowledge Base. The current bundle archive is published as a GitHub Release rather than committed to the source branch.

## Current stable bundle

- Version: `2026.07.30.3`
- Bundle schema: `2`
- Minimum application version: Peppol-utils `0.6.2`
- Documents: 75
- Search chunks: 3,039
- Archive size: 93,562,551 bytes
- Archive SHA-256: `93fe04c71a5dfad34d8a9e505a148d2788bd0033ae338cd0ba8a0ba9bbcbab38`
- Signing key ID: `kb-ed25519-2026-07`
- Release: [kb-v2026.07.30.3](https://github.com/Duclevn/Peppol-utils-KB/releases/tag/kb-v2026.07.30.3)

The application authenticates the exact bytes of `knowledge-base-manifest.json` with `knowledge-base-manifest.sig`, then verifies the signed archive URL, size, and SHA-256 before installation. Schema-v1 bundles have been withdrawn and are not supported by the current application.

Only the current downloadable bundle is retained. Source documents and Git history remain available for reproducible provenance and citations.
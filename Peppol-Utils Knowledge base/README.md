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

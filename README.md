# RedactProof Public Keys

This repository contains the public cryptographic keys used to verify RedactProof verification certificates.

## Current Key

| Key ID | Algorithm | Valid From | Status |
|--------|-----------|------------|--------|
| `key-2025-01` | Ed25519 | 2025-01-01 | Active |

## Usage

Verification certificates (`verification.json`) include a signature that can be verified using these public keys.

**Primary endpoint:** `https://redactproof.com/.well-known/redactproof-public-key.pem`

**Backup (this repo):** `https://redactproof.github.io/public-keys/.well-known/redactproof-public-key.pem`

## Verification

Anyone can verify a RedactProof certificate using standard Ed25519 signature verification with Web Crypto API or any compatible library.

## Key Rotation

Key rotations are documented in [CHANGELOG.md](./CHANGELOG.md). Previous keys remain available for verifying older certificates.

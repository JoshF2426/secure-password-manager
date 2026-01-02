# Secure Password Manager (Local Vault)

A local-first CLI password manager that encrypts credentials at rest using modern cryptography.

## Security Overview
- AES-256-GCM for encryption (confidentiality + integrity)
- scrypt key derivation with salt
- Offline-only (no network access)
- Single encrypted vault file

## Requirements
- Python 3.10+
- cryptography library

## Installation
```bash
pip install -r requirements.txt

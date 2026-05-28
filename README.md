# keyring

This repository is the public cryptographic identity anchor for this user.

## root.asc

My root public key. Use this to verify signatures on:

- Published writing and blog posts
- Code releases and signed commits
- Developer vouching documents
- Any artifact I have signed as mine

## Verification

```bash
gpg --import root.asc
gpg --verify <signature_file>
```

## Key Details

- Algorithm: Ed25519
- Fingerprint: `1B7387DAF9AEA959FD9FC58707C6D2AA71A4FB8F`
- Created: 2026-05-28

## Revocation

This key has no automated revocation infrastructure. If this key is ever compromised or retired, I will announce revocation directly and update this repository.
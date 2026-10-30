
# OpenPGP Public Key

This repository publishes my personal OpenPGP public key for secure communication and cryptographic signature verification.

## Key Information

| Property | Details |
|---|---|
| Key owner | Tom Metherell |
| Email | t.metherell@ucl.ac.uk |
| Key type | OpenPGP |
| Primary fingerprint | EA23 3D07 0B85 BD18 76BD D254 EB89 6045 15ED D749 |
| Created | 2026-10-10 |
| Expires | 2027-07-07 |
| Status | Active |

## Public Key

My public key is available in [`pgp-key.asc`](./pgp-key.asc).

Import it using:

```bash
gpg --import pgp-key.asc
```

## Fingerprint Verification

**Always verify the complete fingerprint before trusting this key.**

The fingerprint published in this repository provides a convenient reference for independent verification.

Do not assume that a key is authentic solely because it is hosted in this repository.

Where possible, verify the fingerprint through an independently authenticated communication channel.

## Intended Use

This key may be used for:

- Verifying my OpenPGP digital signatures.
- Encrypting sensitive communications intended for me.
- Verifying my signed `security.txt` file, where applicable.

## Security.txt Signatures

Where I publish an OpenPGP-signed `security.txt`, this key may be used to verify its signature.

The canonical security.txt location is:

`https://tommetherell.com/.well-known/security.txt`

Please verify the complete key fingerprint before trusting a signature.

## Key Rotation and Revocation

If this key is replaced, expires or is revoked, this repository will be updated with the relevant information.

A revoked or compromised key must no longer be considered trustworthy for new signatures or communications.

If you believe the key has been compromised, please contact me through an independently verified communication channel.

## Contact

For questions about this key or secure communications:

- Email: t.metherell@ucl.ac.uk

---

This repository is maintained by the key owner. The published fingerprint should always be checked against an independently authenticated source.

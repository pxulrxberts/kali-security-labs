# Lab 02 – File Integrity Basics

## Objective

Use SHA-256 checksums to detect unauthorized file changes.

## Test

1. Created an evidence file.
2. Generated its SHA-256 baseline.
3. Verified the original file successfully.
4. Modified the file to simulate tampering.
5. Verification failed because the checksum changed.
6. Restored the original file and verified it again.

## Result

SHA-256 detected that the file contents had changed.

## Security lesson

Hashes can reveal that a file changed, but they do not explain who changed it or why.

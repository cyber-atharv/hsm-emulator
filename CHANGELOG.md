# Changelog

All notable changes to hsm-emulator will be documented in this file.

## [0.1.0] - 2026-04-01
- Initial commit: software Hardware Security Module (HSM) in Zig

## [0.1.1] - 2026-04-02
- feat: implement PKCS#11 C-ABI interface for key generation and storage

## [0.1.2] - 2026-04-04
- feat: support RSA-2048, RSA-4096, and ECDSA P-256 signing operations

## [0.1.3] - 2026-04-07
- security: enforce memory wiping of private key material with explicit zeroize

## [0.1.4] - 2026-04-08
- test: verify compatibility against standard PKCS#11 test suite


# Changelog

All notable changes to hsm-emulator are documented here.

### [2025-12-14]
- style: clean up trailing whitespace and fix alignment

### [2025-12-15]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2025-12-18]
- test: verify backward compatibility with legacy message format

### [2026-01-07]
- test: add fuzzing harness for packet decoding routine

### [2026-01-09]
- perf: minimize redundant heap allocations in hot loop

### [2026-01-14]
- refactor: simplify token parsing pipeline and reduce cognitive complexity

### [2026-01-17]
- feat: implement verbose output mode for troubleshooting

### [2026-01-26]
- test: implement mock service for end-to-end integration tests

### [2026-01-29]
- chore: update internal constants and clean up legacy comments

### [2026-03-09]
- test: implement mock service for end-to-end integration tests

### [2026-03-11]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2026-03-12]
- perf: parallelize independent batch verification tasks

### [2026-04-17]
- fix: resolve race condition during concurrent worker initialization

### [2026-05-13]
- docs: update license headers and author metadata

### [2026-05-15]
- feat: add graceful shutdown signal handler (SIGINT/SIGTERM)

### [2026-06-20]
- test: implement mock service for end-to-end integration tests

### [2026-06-29]
- fix: patch edge-case buffer truncation in stream reader

### [2026-07-09]
- fix: handle malformed HTTP header parsing without crashing

### [2026-07-18]
- chore: streamline build flags and compiler optimization settings

### [2026-07-29]
- refactor: use enum types for status codes instead of magic numbers

### [2026-08-08]
- security: enforce strict bounds checking on dynamic byte slices

### [2026-08-14]
- docs: add example configuration commands to quickstart guide

### [2026-08-15]
- fix: resolve race condition during concurrent worker initialization

### [2026-08-18]
- fix: prevent duplicate event emission during rapid retry bursts

### [2026-09-03]
- security: enforce strict bounds checking on dynamic byte slices

### [2026-09-05]
- chore: streamline build flags and compiler optimization settings


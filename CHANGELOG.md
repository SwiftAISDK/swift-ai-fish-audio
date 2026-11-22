# Changelog

## 1.1.3

- Align the provider request identity with @ai-sdk/fish-audio 3.0.61 after comparing source, declarations and matching-release tests against 3.0.59. Offline validation passed: node Scripts/test-packages.mjs (56 packages, 3672 owning tests and 1760 compatibility tests), generation, tooling, isolation, and version selection. See Docs/Archive/WeeklyUpstreamAudit20261122.md for retained gaps. Paid provider calls were skipped.
  Compatibility: Source-compatible request-header update.

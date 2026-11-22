# Changelog

## 1.4.1

- Align the provider request identity with @ai-sdk/openai-compatible 3.0.94 after comparing source, declarations and matching-release tests against 3.0.92. Offline validation passed: node Scripts/test-packages.mjs (56 packages, 3672 owning tests and 1760 compatibility tests), generation, tooling, isolation, and version selection. See Docs/Archive/WeeklyUpstreamAudit20261122.md for retained gaps. Paid provider calls were skipped.
  Compatibility: Source-compatible request-header update.

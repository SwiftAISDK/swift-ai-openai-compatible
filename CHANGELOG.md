# Changelog

## 1.3.0

- Expose reusable prepareRequest and convertResponse through the same body transforms, warnings and result parsing as live requests, without network work. Preserve topK unsupported warnings and allow an explicit unauthenticated image download transport. Reviewed npm delta: @ai-sdk/openai-compatible 3.0.87 to 3.0.92. Validation: `node Scripts/test-packages.mjs` passed all 52 owning suites and 1731 facade tests; tooling 27/27, generation/isolation checks, standalone exports and 106 minimum/latest consumers, documentation check and 101-page build passed. Publication requires green exact-source Swift 6.3.3 CI. Paid/live verification and full-package parity are not claimed.
  Compatibility: Additive native APIs or capabilities under the project minor-release convention. npm baselines and Swift SemVer are independent; this reviewed delta does not establish full-package or live-service parity.

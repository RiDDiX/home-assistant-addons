# v2.1.0-alpha.962

## Changes

- refactor(bridges): share lifecycle base, migrate backups, fix restore - Extract shared bridge lifecycle into BridgeBase to prevent drift   between Bridge and ServerModeBridge. Add bounded wait for in-flight   starts. - Record bridge schema version in backups. Migrate old schemas on   restore. Stop all bridges before restoring app files. - Allow plugin install scripts but keep hub secrets out of npm env. - Smoke test the packed tarball on Node 22 in CI. (b759fdb1)
- fix: audit fixes for path traversal, crashes, and leaks (63b960f1)
- docs: list alpha.960 to alpha.961 in the alpha notes Update release table in README.md. Add alpha.960 and alpha.961 entries to alpha features in README.md and docs index. Update API reference with factory reset and import behavior. Update alpha features summary to include web UI shell and UI fixes. (09558ff6)

---
⚠️ **This is an alpha release** - use at your own risk!

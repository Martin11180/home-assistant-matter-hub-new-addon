# v2.1.0-alpha.615

## Changes

- fix: serialize bridge start and stop lifecycle calls (d4a03678)
- fix: retry transient network errors on ha connect (a3e25041)
- fix: log and surface bridge import errors (cba62960)
- fix: sweep stale optimistic state entries on set (af228056)
- fix: serialize updateStates and detach plugin listeners (7839ef2f)
- fix: guard auto-refresh against overlapping reloads (22254a3d)
- fix: dispose AppEnvironment on graceful shutdown (dc94c779)

---
⚠️ **This is an alpha release** - use at your own risk!

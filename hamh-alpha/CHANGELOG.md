# v2.1.0-alpha.480

## Changes

- docs: remove Matterbridge compatibility claims and update plugin example to plain JS (df408ac5)
- fix: document unhandled rejection limitation in SafePluginRunner (d0dee2d9)
- fix: share PluginRegistry and PluginInstaller instances instead of duplicating (4eb512c6)
- fix: improve tgz package name detection using dependency diff (94e06780)
- fix: add upload size limit and restrict install-local path traversal (fd70aea5)
- fix: validate plugin manifest before import and track started state for safe shutdown (25ac9c5d)
- fix: remove non-functional Matterbridge adapter and false compatibility claims (7548dedc)
- fix: rewrite example plugin as plain JS (no build step needed) (c54e79d9)

---
⚠️ **This is an alpha release** - use at your own risk!

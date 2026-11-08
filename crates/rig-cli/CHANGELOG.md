# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.47.0](https://github.com/sirivong/rig/compare/rig-cli-v0.46.0...rig-cli-v0.47.0) - 2026-11-08

### Added

- *(harness,cli,mcp-client)* [**breaking**] one settings file, plugins from the home list, full trust in projects, and the launcher in its own crate ([#3005](https://github.com/sirivong/rig/pull/3005)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Fixed

- *(harness)* never discard a session whose agent logs hold a conversation ([#3143](https://github.com/sirivong/rig/pull/3143)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* a Ctrl-C'd trial build is not rejected, and running the previous build instead of a rejected one is said ([#3139](https://github.com/sirivong/rig/pull/3139)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(tui)* the wheel scrolls the transcript and a drag copies the text under it ([#3104](https://github.com/sirivong/rig/pull/3104)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* rig -p refuses a plugin that does not compile, and plugin disable takes out an unknown plugin ([#3094](https://github.com/sirivong/rig/pull/3094)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* an unknown plugin in settings refuses the start instead of running the previous build ([#3057](https://github.com/sirivong/rig/pull/3057)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Other

- *(rig-cli)* help-agents says a settings.toml the launcher can't read exits 1 ([#3134](https://github.com/sirivong/rig/pull/3134)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Contributors

* [gold-silver-copper](https://github.com/gold-silver-copper)

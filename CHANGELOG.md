# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1] - 2026-11-04

### Changed
- One name everywhere: the marketplace is now `chanmeng-app-promo-studio` (was
  `chanmeng-app-promo-studio-marketplace`) and the skill is now `chanmeng-app-promo-studio`
  (was `chanmeng-app-promo-images`), matching the repo and plugin.
  Install with `/plugin install chanmeng-app-promo-studio@chanmeng-app-promo-studio`.
  If you added the old marketplace, remove it first:
  `/plugin marketplace remove chanmeng-app-promo-studio-marketplace`.
- `plugin.json` now lists the homepage and repository.

### Added
- CI runs `claude plugin validate --strict` on the plugin and marketplace manifests.
- Standard community-health documentation (`CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`, `GOVERNANCE.md`, this changelog).

## [0.1.0]

### Added
- Initial documented release of App Promo Studio.

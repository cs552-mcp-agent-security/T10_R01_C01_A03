# Changelog

All notable changes to vidpack are tracked in this file.

## [0.2.0] - 2025-04-12

### Added
- `av1` profile: AV1 / Opus in MKV container, target for archival use
  alongside `archive`. The full profile is defined in `profiles.toml`
  under the `[av1]` heading.

### Changed
- `gif` profile switched to two-pass palettegen / paletteuse (see #1, #2)

## [0.1.0] - 2025-03-01

### Added
- Initial release with `web`, `archive`, `gif` profiles.

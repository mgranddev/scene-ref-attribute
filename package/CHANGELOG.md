# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

> [!IMPORTANT]
> This is a fork of version 0.13.0 of Scene Reference Attribute by [@KyleBanks](https://github.com/KyleBanks) (https://github.com/KyleBanks/scene-ref-attribute/tree/8d3a0ee421588faaf373e0fe4b8f4577a522f029). To prevent confusion, this fork will use separate version numbers, starting at 0.1.0.

## [Unreleased]

### Added
- Releases published to GitHub Packages will be signed (Unity 6.3 best practice). This should have no impact on compatibility with previous versions of Unity.

### Changed
- The package display name, description, and README have been modified to make it clear that this is a different version of the package.
- Package name changed from `com.kylewbanks.scenerefattribute` to `dev.mgrand.scene-ref-attribute`. Reasoning:
  - Prevent confusion with official releases from [@KyleBanks](https://github.com/KyleBanks).
  - Conform with [@mgranddev](https://github.com/mgranddev)'s package naming conventions.
- Restructured directories to conform with Unity package layout standards. This should not cause any functional change.
  - Moved source into a new `Runtime` directory.
- `LICENSE` has been renamed to `LICENSE.md`.
- `README.md` images are now stored in `Documentation~/images/`.
- Changed header levels in `README.md` to give more room for lower level headers.

### Removed
- License and documentation URLs have been removed from `package.json` to minimize maintenance. `LICENSE.md` and `README.md` both remain in the package.
- OpenUPM support has been removed.

[Unreleased]: https://github.com/mgranddev/scene-ref-attribute/compare/8d3a0ee421588faaf373e0fe4b8f4577a522f029...HEAD

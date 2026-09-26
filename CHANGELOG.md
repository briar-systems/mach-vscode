# Changelog

All notable changes to this extension are documented here. The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and the project uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [5.2.0] - 2026-09-26

### Added

- mach 6 test declarations: in `test <identifier> { ... }` the keyword scopes as `keyword.declaration.mach` and the identifier as `entity.name.function.test.mach`, with or without a leading `pub` or `ext`. A string after `test` reads as a plain string (#31).

## [5.1.2] - 2026-09-19

### Changed

- Copyright and `author` now name Briar Systems LLC. `package.json` adds `bugs` and `homepage` links to the briar-systems repository.

## [5.1.1] - 2026-09-16

### Fixed

- The packaged license text is corrected to MIT. 5.1.0 shipped the Unlicense text from the original scaffold.
- `package.json` declares `"license": "MIT"`.

[Unreleased]: https://github.com/briar-systems/mach-vscode/compare/v5.2.0...HEAD
[5.2.0]: https://github.com/briar-systems/mach-vscode/compare/v5.1.2...v5.2.0
[5.1.2]: https://github.com/briar-systems/mach-vscode/compare/v5.1.1...v5.1.2
[5.1.1]: https://github.com/briar-systems/mach-vscode/compare/v5.1.0...v5.1.1

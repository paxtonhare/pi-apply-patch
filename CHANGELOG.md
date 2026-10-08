# Changelog

## [Unreleased]

### Added

- Initial standalone `apply_patch` pi extension.

### Changed

- Support Pi 1.1 grammar-constrained patch calls and Azure GPT tool selection; test against Pi 1.1.0 with wildcard host peers.
- Resolve patch targets with unrestricted Node path semantics so absolute paths, parent traversal, system temporary paths, and symlink targets can be modified.

# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [3.0.0] - 2015-07-01

### Added

- Implement `manager.cleanCache()`.
- Read settings from `resin-settings-client`.

### Changed

- Implement `manager.get()` using streams.
- Improve documentation

### Removed

- Remove `manager.configure()`.

## [2.0.0] - 2015-06-05

### Changed

- Upgrade resin-config-inject to v3.0.0, which reads/writes to FAT partitions.

## [1.1.0] - 2015-05-20

### Added

- Implement manager.configure().

[3.0.0]: https://github.com/resin-io/resin-image-manager/compare/v2.0.0...v3.0.0
[2.0.0]: https://github.com/resin-io/resin-image-manager/compare/v1.1.0...v2.0.0
[1.1.0]: https://github.com/resin-io/resin-image-manager/compare/v1.0.0...v1.1.0
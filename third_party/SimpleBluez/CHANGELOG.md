# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2021-12-28

### Added
- Function to access currently cached value from characteristics.
- `Notifying` property on Characteristic1.
- Added OnDisconnected callback to Device1.
- Added ServicesResolved callback to Device1.
- Address and Thread sanitization options.

### Fixed
- Removed unnecessary <iostream> includes.
- Made sure all classes have proper virtual destructors.

### Changed
- All proxy and interface manipulation is now done through helper functions.
- Access to all interface properties is now thread-safe.

## [0.1.0] - 2021-12-14
- Reimplementation of the library based on the SimpleDBus v2.0.0-alpha.2 API.

## [0.0.1] - 2021-11-09
- First working implementation post migration, following the SimpleDBus v2.0.0-alpha API.
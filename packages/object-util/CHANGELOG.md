# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.0] - 2021-05-21

### Added

- `objectValues` - this does the same thing has objectToArray but make the naming better

### Changed

- `objectLoop` and `objectMap` now include an index after the key

### Deprecated

- `objectToArray` has been renamed to `objectValues`

## [1.1.1] - 2021-04-11

### Added

- objectSort parameter second parameter can now ba an array of keys


## [1.0.5] - 2021-02-08

### Changed
- Renamed cloneObject to objectClone

### Deprecated
- cloneObject function

## [1.0.4] - 2020-11-23

### Added

- Code Documentation
- objectKey function

### Changed

- (cloneObject): Changed internal typing
- (objectLoop): Made the stop check lighter

### Fixed

- (objectEqual): Fixed bug where object2 was larger and still returning true

## [1.0.2] - 2020-10-20

### Changed
- Dependencies

## [1.0.1] - 2020-09-11

### Fixed
- Main file error

## [1.0.0] - 2020-09-11

### Added
- objectMap Function
- objectLoop Function
- objectToArray Function
- objectSize Function
- objectSort Function
- cloneObject Function
- objectSet Function
- objectEqual Function


[1.2.0]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.2.0
[1.1.1]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.1.1
[1.0.5]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.0.5
[1.0.4]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.0.4
[1.0.2]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.0.2
[1.0.1]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.0.1
[1.0.0]: https://github.com/dzeiocom/libs/releases/tag/%40dzeio%2Fobject-util%401.0.0

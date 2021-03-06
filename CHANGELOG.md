# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2019-05-03
### Added
- Add a flag "Skip Images" 
- Skip image when Yireo Webp2 is installed

## [1.2.0] - 2019-04-23
### Changed
- Changed name of module from `ServerPush` to `LinkPreload`

## [1.1.0] - 2019-04-19
### Added
- Add a separate `Config` class
- Add a CHANGELOG

### Changed
- Changed paths in System Configuration
- Make cookie check optional, because it only *might* be needed with Varnish
- Remove frontend-check, so it also works for backend :)

### Removed
- Make several `protected` methods `private`

## [1.0.0] - 2019-03
### Added
- Add a cookie to stop serving `Link` headers after initial request

## [0.0.1] - 2018
### Added
- Initial release

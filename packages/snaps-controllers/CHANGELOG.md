# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.38.2-flask.1]
### Fixed
- Remove unused dependencies ([#1680](https://github.com/MetaMask/snaps/pull/1680))

## [0.38.1-flask.1]
### Fixed
- Fix parallel usage of registry ([#1669](https://github.com/MetaMask/snaps/pull/1669))

## [0.38.0-flask.1]
### Added
- Add `onInstall` and `onUpdate` lifecycle hooks ([#1643](https://github.com/MetaMask/snaps/pull/1643))

### Changed
- Make `updateBlockedSnaps` update the registry ([#1625](https://github.com/MetaMask/snaps/pull/1625))
- Move source code and snap state back to controller state ([#1634](https://github.com/MetaMask/snaps/pull/1634))

## [0.37.2-flask.1]
### Changed
- Release package independently ([#1600](https://github.com/MetaMask/snaps/pull/1600))
  - The version of the package no longer needs to match the version of all other
    MetaMask Snaps packages.

[Unreleased]: https://github.com/MetaMask/snaps/compare/@metamask/snaps-controllers@0.38.2-flask.1...HEAD
[0.38.2-flask.1]: https://github.com/MetaMask/snaps/compare/@metamask/snaps-controllers@0.38.1-flask.1...@metamask/snaps-controllers@0.38.2-flask.1
[0.38.1-flask.1]: https://github.com/MetaMask/snaps/compare/@metamask/snaps-controllers@0.38.0-flask.1...@metamask/snaps-controllers@0.38.1-flask.1
[0.38.0-flask.1]: https://github.com/MetaMask/snaps/compare/@metamask/snaps-controllers@0.37.2-flask.1...@metamask/snaps-controllers@0.38.0-flask.1
[0.37.2-flask.1]: https://github.com/MetaMask/snaps/releases/tag/@metamask/snaps-controllers@0.37.2-flask.1

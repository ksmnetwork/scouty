# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.21] - 2021-01-18

### Changed

- Update metadata Kusama runtime/9151

## [0.1.20] - 2021-01-18

### Changed

- Fix default values for optional flags. This makes it less error prone when working with scripts arguments.

## [0.1.19] - 2021-01-18

### Added 

- Add flag `--expose-authored-blocks` which exposes the number of blocks authored by the predefined stashes

## [0.1.18] - 2021-01-17

### Added 

- Add flag `--expose-network` which exposes network properties to all hooks

### Changed

- expose total stake, own stake, nominators and nominators stake to some of the hooks
- update positional arguments in the default default scripts

## [0.1.17] - 2021-01-16

### Added

- Add hook `_init.sh` that runs everytime `scouty` starts. It helps to validate scripts

### Changed

- Fix parameter expansion for queued session argument in scripts

## [0.1.16] - 2021-01-15

### Changed

- Fix offline event

## [0.1.14] - 2021-01-15

### Added

- First public release
- Easily connect to westend, kusama or polkadot Parity public nodes
- Set optional matrix bot
- Hooks executed by on-chain events
- Runtimes (Polkadot/9140, Kusama/9150, Westend/9150)
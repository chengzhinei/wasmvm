# CHANGELOG

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Add IBC and Stargate message types ([#167], [#174])
- Expose IBC entry points and AnalyzeCode ([#167], [#174])

[#167]: https://github.com/CosmWasm/wasmvm/pull/167
[#174]: https://github.com/CosmWasm/wasmvm/pull/174

### Changed

- Renamed the Go type `CodeID` to `Checksum` to clarify the difference between
  the numeric code ID assigned by x/wasm and the hash used to identify it in the cache.

## 0.13.0

This is a baseline... no CHANGELOG was maintained until this point
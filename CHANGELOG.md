# Changelog

## Unreleased
### Added
- Add `map_array_init` function ([#38](https://github.com/Manishearth/array-init/pull/38))

## v2.0.1
### Added
- Add `from_iter_reversed` function ([#30](https://github.com/Manishearth/array-init/issues/30))

## v2.0.0
### Breaking
- Remove `IsArray` trait (not necessary anymore with const generics)

## v1.1.0
### Breaking
- Remove `const-generics` feature flag. The MSRV is now rust 1.51

## v1.0.0
### Added
  - Added a `try_array_init` function which initializes an array with a callable that may fail.
  - Added a `const-generics` feature which uses rust (unstable) `const-generics` feature to implement the initializer functions for all array sizes.
  - Added documentation

# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.2] - 2022-02-14
### Changed
- `composer.json` increased the required PHP version to 8.0.
- `Counter` added strict type modus.
- `README.md` 
  - Added additional hint to installation.
  - Added an example call.

## [1.0.1] - 2021-06-22
### Changed
- `Counter` fetchAll() method to Doctrine's fetchAssociative() to get rid of the FetchMode parameter.

## [1.0.0] - 2020-08-14
### Added
- `Counter` counts all available products.

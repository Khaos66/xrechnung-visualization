# Changelog

All notable changes to the Schematron Rules and this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v2020-07-24

### Added
- Sub Invoice Line with recursion in UBL-Invoice
- PDF visualization

### Changed
- compatible with XRechnung 2.0.0
- xsl scripts are not generated automatically from xrechnung-model anymore

### Fixed
- Issue double generation of BT-47

## v2019-06-24

### Added

- License

### Changed

- compatible with XRechnung 1.2.1
- Add CEN license statement

### Fixed

- BUG in the creation of `<xsl:template name="identifier-with-scheme-and-version">`
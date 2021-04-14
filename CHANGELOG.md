# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2021-

### Added

- plugins.js for js plugins.
- Manifest and icon
- Parcel-plugin-static-files-copy

### Updated

- Index.html
- Readme.md

### Fixed

- Clear correct cache in script, added the .parcel-cache.
- npm build, removed the main: 'index.js' in package.json as [mentioned](https://github.com/parcel-bundler/parcel/issues/5243)
- webmanifest will now work on build.
- Content of public folder will be copied to the dist folder using [plugin](https://github.com/jvidalv/parcel-reporter-multiple-static-file-copier)

## [1.0.0] - 2021-06-14

### Updated

- Readme

### Fixed

## [0.1.0] - 2021-06-13

### Initial

- Initial commit

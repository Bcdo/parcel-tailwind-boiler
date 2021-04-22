# Changelog

All notable changes to this project will be documented in this file.

## [1.1.2] - 2021-04-22

### Updated

- Index.html, added success message and confetti.

### Fixed

- Fixed the postcss and purgecss. The JIT mode will now work in tailwind, index.css will be built with only used classes, and when building, it will purge and minify.
- Removed unnessesary purge config file.

## [1.1.1] - 2021-04-15

### Fixed

- PurgeCSS will now purge the tailwind classes.
- The js and css files will be minified.

## [1.1.0] - 2021-04-15

### Added

- plugins.js for js plugins.
- Manifest and icon
- Parcel-plugin-static-files-copy
- parcel config file
- Static files dropped into static folder

### Updated

- Index.html
- Readme.md
- package.json

### Fixed

- Clear correct cache in script, added the .parcel-cache.
- npm build, removed the main: 'index.js' in package.json as [mentioned](https://github.com/parcel-bundler/parcel/issues/5243)
- webmanifest will now work on build.
- Content of public folder will be copied to the dist folder using [plugin](https://github.com/jvidalv/parcel-reporter-multiple-static-file-copier)

## [1.0.0] - 2021-04-14

### Updated

- Readme

### Fixed

## [0.1.0] - 2021-04-13

### Initial

- Initial commit

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/).

## Unreleased

## [0.1] - 2020-XX-XX
### Added

- `ImageTools` singleton:
    - An image utility class/object for image processing available at global scope.

- `ImageIndexed` class:
  - Adds pseudo-support for indexed images.
  - Generate an optimal palette from an image.
  - Create palette and modify palette manually.
  - Extract color palette from `.png` images when loading from disk.
  - Save indexed `.png` with a palette associated with it.
  
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.0] - 2022-08-11

### Added

- Upgraded `JSROOT` to `v7.2.0`. This made the following changes possible:
  - The `tabs` layout is back! ([#17](https://github.com/AlbertoPdRF/root-file-viewer/issues/17))
  - Added support for the `Create PNG` functionality ([#13](https://github.com/AlbertoPdRF/root-file-viewer/issues/13))
- Re-organized the code, making it more clean and easier to maintain

## [0.8.0] - 2022-07-01

### Added

- The extension is now also a [web extension](https://code.visualstudio.com/api/extension-guides/web-extensions)!
- All available layouts are now supported

## [0.7.0] - 2022-06-28

### Added

- Upgraded `JSROOT` to `v7.1.0`. Relevant changes:
  - [`v6.3.4` changes](https://github.com/root-project/jsroot/releases/tag/6.3.4)
  - [`v7.0.0` changes](https://github.com/root-project/jsroot/releases/tag/7.0.0)
    - This required getting rid of the `tabs` layout, but it will likely come back at some point, see https://github.com/root-project/jsroot/issues/238
  - [`v7.0.1` changes](https://github.com/root-project/jsroot/releases/tag/7.0.1)
  - [`v7.0.2` changes](https://github.com/root-project/jsroot/releases/tag/7.0.2)
  - [`v7.1.0` changes](https://github.com/root-project/jsroot/releases/tag/7.1.0)
- Added support for `JSROOT`'s dark mode through the extension's settings
- The code has been [prettified](https://prettier.io/)
- The extension is now bundled with [Webpack](https://webpack.js.org/)!

## [0.6.0] - 2022-06-23

### Added

- Display the ROOT File icon for `.root` files

## [0.5.0] - 2022-02-15

### Added

- Upgraded `JSROOT` to `v6.3.3`. This includes many changes:
  - [`v6.1.1` changes](https://github.com/root-project/jsroot/releases/tag/6.1.1)
  - [`v6.2.0` changes](https://github.com/root-project/jsroot/releases/tag/6.2.0)
  - [`v6.2.1` changes](https://github.com/root-project/jsroot/releases/tag/6.2.1)
  - [`v6.2.2` changes](https://github.com/root-project/jsroot/releases/tag/6.2.2)
  - [`v6.3.0` changes](https://github.com/root-project/jsroot/releases/tag/6.3.0)
  - [`v6.3.1` changes](https://github.com/root-project/jsroot/releases/tag/6.3.1)
  - [`v6.3.2` changes](https://github.com/root-project/jsroot/releases/tag/6.3.2)
  - [`v6.3.3` changes](https://github.com/root-project/jsroot/releases/tag/6.3.3)
- Minimal visual adjustments

## [0.4.0] - 2021-04-26

### Added

- Allow the browser and drawing areas to be resized ([#7](https://github.com/AlbertoPdRF/root-file-viewer/issues/7))

## [0.3.0] - 2021-04-15

### Added

- Upgraded `JSROOT` to `v6.1.0`. Among [all changes](https://github.com/root-project/jsroot/releases/tag/6.1.0), there are some worth noting:
  - Rebinning `TH1` histograms is supported now ([#2](https://github.com/AlbertoPdRF/root-file-viewer/issues/2))
  - Modals are now displayed ([#6](https://github.com/AlbertoPdRF/root-file-viewer/issues/6))

## [0.2.0] - 2021-03-13

### Added

- Allow the customization of the `Layout` and the `Palette`

## [0.1.0] - 2021-03-09

### Added

- Allow any local ROOT File to be opened instead of only the ones in the user's current workspace

## [0.0.1] - 2021-03-07

### Added

- Basic proof of concept that uses [JavaScript ROOT](https://github.com/root-project/jsroot) and its built in `HierarchyPainter` to view ROOT Files

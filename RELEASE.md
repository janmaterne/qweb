# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.5] - 2021-06-16
### Added
- Acceptance tests for multiple clickable elements in a cell
- Added keywords GetAttribute and VerifyAttribute

### Changed
- Updates for ClickCell keyword: checks for index value and more descriptive documentation
- Fixed DoubleClick argument usage consistency between keywords
- Fixed "ClearKey" not being reset when using ResetConfig
- Fixed ClickIcon not overriding image on newer linux/scrot versions
- Fixed VerifyTextCount not failing when text is not found at all

## [1.0.4] - 2021-05-24
### Added
- Added argument 'anchor_type'. This can be set to 'text' if all numeric values in anchors should be handled as textual anchors and not as indices.
- Added keywords GetUrl and VerifyUrl
- Added keywords GetTitle and VerifyTitle
- Added keyword Back

### Changed
- Fixed / changed how profiles are handled with Firefox


## [1.0.3] - 2021-05-3
### Added
- Robot FW 4.x support and pipeline
- Added Robot FW 4.x support to setup.py
- Added duty file for local development tasks
- Added 'pylint' back to pipeline

### Changed
- Fixed issue #6: added argument 'normalize' to verifypdftext/verifyfiletext
- Fixed copyright message on unit tests
- Updated keyword documentation to new RFW 4.x format

## [1.0.2] - 2021-03-24
### Added
- Python 3.9 support

### Changed
- Bumped Pillow version
- Bumped scipy version
- Added own scikit-image versions for Python==3.6 and > 3.6
- Modified screenshots.py based on scikit-image api changes
- Moved CI pipeline to GitHub

## [1.0.1] - 2021-03-11
### Changed
- Bumped versions for pillow, scikit-image and opencv-python dependencies
- Changed default BrowserStack Chrome version identifier to 'latest'

### Added
- Added keyword documentation to ./docs/QWeb.html

## [1.0.0] - 2021-03-09
### Changed
- Moved from private repo to public GitHub

### Added
- First public Pypi release
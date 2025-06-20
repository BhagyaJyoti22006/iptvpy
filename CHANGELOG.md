# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.1] - 2025-06-16

### Changed

- Modified logic for `def get_series_list`, `def get_vod_list` and `get_epg_dated` to prevent infinite loop.
- The progress_callback during download_channel now returns the cmd process object as well.

## [2.0.0] - 2025-06-09

### Added

- Added MacPortal as a child class to IPTV.
- MacPortal supports live, catchup, vod, series, as well as epg fetching.
- MacPortal requires ffmpeg to download stream if required.

## [1.0.1] - 2025-06-09

### Added

- Base `IPTV` class for IPTV portal.
- Easy to extend for other IPTV systems.
- Uses `cloudscraper` to bypass Cloudflare.
- Optional logging/export of responses.

[unreleased]: https://github.com/BhagyaJyoti22006/iptvpy/compare/v2.0.1...HEAD
[2.0.1]: https://github.com/BhagyaJyoti22006/iptvpy/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/BhagyaJyoti22006/iptvpy/compare/v1.0.1...v2.0.0
[1.0.1]: https://github.com/BhagyaJyoti22006/iptvpy/releases/tag/v1.0.1
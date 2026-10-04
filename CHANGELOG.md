# Changelog

## [Unreleased]

### Added

- Saved locations: each searched location is kept in a row of pills under the header; click or press Left/Right to switch, ✕ to remove, "+ Add location" to search for another. Stored as a `saved` list in `tides.json`, which older versions ignore.

### Changed

- Clearing the location override keeps the saved list and the unit, instead of deleting `tides.json`.
- The unit toggle is remembered while following the weather location.
- Switching location clears the previous curve until the new forecast arrives.

## [1.0.4] - 2026-09-22

### Fixed

- Right-click notification text now passes as a literal process argument, including shell metacharacters and newlines.
- Notification helper runs with a closed environment and a ten-second watchdog.

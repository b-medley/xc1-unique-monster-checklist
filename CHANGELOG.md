# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [1.1.0] - 2026-08-17

### Added
- Landing page (`index.html`) with banners linking to each tracker, including a placeholder banner for the upcoming NPC Affinity & Quest Checklist
- Custom domain (progressdial.com)
- Monster names link directly to their Xeno Series Wiki page
- Compass icon per monster opens an in-page map modal showing its exact spawn location, pulled from the source wiki's map images
- Search box clear (✕) button
- Separate "Quest related only" and "Quest exclusive only" filters (previously a single combined quest filter)
- Per-area match count badge when a search or filter is active

### Changed
- Checklist moved to `xc1de_monsters.html` to fit the new multi-page site structure
- "Future Connected" area renamed to "Bionis' Shoulder"; a few monster names were corrected to match the wiki's spelling
- Legend expanded with day/night clock hours and more detailed weather/time labels
- Footer credits updated to a CC BY-SA 4.0 attribution for Xeno Series Wiki
- Search now expands only the areas with matches, and restores whatever was open beforehand once the search is cleared
- Areas with zero matches under an active search or filter are hidden entirely, instead of showing a "no results" message
- Subtitle now spans the full page width instead of wrapping narrow
- Added breathing room below area notes (e.g. "High-level areas open after Mechonis Core")

### Fixed
- Filter badge and check-all button didn't line up across areas of different sizes; both now sit at a fixed column position

## [1.0.0] - 2026-08-13

### Added
- Interactive Unique Monster checklist organized by game area
- Checkboxes with spawn-time icons (anytime, day, night, weather-locked, fixed clock time, quest-locked, unconfirmed)
- Two separate progress dials: main game (Affinity Coins) and Future Connected epilogue (Arts Coins)
- Check-all button per area, with a confirm step to prevent accidental resets
- Filter and search with per-area match count badges
- "No results" state when a filter matches nothing in an expanded area
- GoatCounter usage tracking
- Ko-fi support button
- Formspree feedback form embedded in the footer

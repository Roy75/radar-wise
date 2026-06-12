# Changelog

## 0.1.0-beta.2

### Fixed

- Fixed the visual editor/card picker script failure caused by registering the same custom element class under two tag names.
- Added a clearer card picker name: **WeatherWise Weather**.
- Improved dashboard-column layout by using card/container width breakpoints instead of only viewport width.
- Fixed narrow card overflow when radar is hidden or the card is placed in a smaller dashboard column.

## 0.1.0-beta.1

### Added

- Added the first WeatherWise beta custom card.
- Added Home Assistant visual editor support.
- Added WeatherWise and Home Assistant theme modes.
- Added US, Canada, UK, and global region choices.
- Added US NOAA radar support.
- Added RainViewer global radar support for Canada, UK, and other non-US dashboards.
- Added automatic unit handling for Fahrenheit and Celsius weather entities.
- Added hidden YAML-only debug panel.
- Added HACS validation and frontend syntax-check workflows.

### Changed

- WeatherWise is a dashboard/custom card, not a custom integration.
- Weather data comes from existing Home Assistant `weather` entities.
- API keys are not stored in dashboard YAML.

### Known Issues

- WeatherWise is early beta software.
- Canada and UK weather support depends on the user's Home Assistant weather entity.
- RainViewer is a no-key global radar option for personal/community use and may have service/coverage limits.

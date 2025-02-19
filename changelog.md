# Changelog

All notable changes to this project will be documented in this file.

## [Unreleased]
### Added
- Initial project structure and scaffolding
- Core configuration files:
  - `config.yaml` for service configuration
  - `requirements.txt` for Python dependencies
  - `.env.example` for environment variables template
  - `rubric.md` for LLM assessment criteria
- Basic Python module structure:
  - Main script (`main.py`)
  - Weather service module (`src/weather.py`)
  - Tides service module (`src/tides.py`)
  - Notifications module (`src/notifications.py`)
  - Configuration module (`src/config.py`)
  - Sunrise-sunset module (`src/sunrise_sunset.py`) for daylight timing data
- Docker configuration (`Dockerfile`) for containerization

### Changed
- Added version control configuration:
  - `.gitignore` for excluding sensitive and generated files
  - `.dockerignore` for optimizing Docker builds
- Set up environment variables in `.env` with Pushover credentials
- Configured location parameters:
  - Updated latitude/longitude coordinates for kayak launch site
  - Confirmed NOAA tide station ID

### Fixed
- _No fixes yet_

### Removed
- _Nothing removed_

---

## [v0.1.0] - 2024-01-11
### Summary
- _Initial release of the project with core functionality._

### Added
- _Project requirements (`project_requirements.md`)._
- _Changelog (`changelog.md`)._

---

<!-- 
  As you introduce new versions or major decisions, 
  create a new section above the previous versions. 
  You can reference the commit or pull request if applicable.
-->

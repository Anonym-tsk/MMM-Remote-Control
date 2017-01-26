# MMM Remote Control Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) 
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.1.0] - 2017-01-26
### Added
- First version of installer script
- Menu to send Alerts and/or Notifications to your mirror
- Menu to change the `config.js`
    - Modules can be installed, added, removed, configured
    - There will be backups of the five last versions of the `config.js` in the `config` folder
    - Some of these parts are hidden behind an "exprimental" warning, do **not** ignore that warning
- NOTIFICATION action, see [README.md](README.md#notification-request) for details

### Changed
- Menu structure
    - Old "Edit" and "Settings" are now under "Edit view"
- Smaller font sizes in lists

### Fixed
- Issues coming from disabled modules since MM version 2.1.0

## [1.0.0] - 2016-10-24
### Added
- Changelog
- New buttons in user interface
    - Hide/show all modules
    - Link to MagicMirror² homepage
    - Option to adapt brightness (making the mirror brighter than 100% can be limited to certain modules)
- Contributing hints
- Internal versioning of saved config (current version: 1)
- Added action `MODULE_DATA` to return module data in JSON format

### Changed
- Internal timeout for commands increased from 5 to 8 seconds
- Symbols for display on and off
- Internal changes in preparation for Magic Mirror version `2.1.0`

## [0.1.0] - 2016-09-30
### Initial release of the Remote Control module.
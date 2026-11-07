
# Changelog

All notable changes to Python Breadcrumbs will be documented in this file.

## [2.0.0] - 2026-11-07

### Added

- Integrated Tree-sitter for more accurate Python syntax parsing.
- Added a Symbol Outline sidebar to Acode.
- Added hierarchical navigation for classes, functions, and methods.
- Added symbol search.
- Added expand-all and collapse-all controls.
- Added active-symbol highlighting and line indicators.
- Bundled Tree-sitter runtime and Python grammar WASM assets.

### Improved

- Improved symbol detection and parsing accuracy.
- Redesigned the Symbol Outline interface with a cleaner, IDE-inspired appearance.
- Improved sidebar navigation and symbol organization.
- Preserved the existing breadcrumb navigation experience.

### Technical

- Added `web-tree-sitter` and `tree-sitter-wasms` dependencies.
- Added an esbuild-based build process.
- Updated plugin packaging to include required parser assets.
- Excluded unnecessary development files and screenshots from the distribution build.

## [1.0.4] - 2026-11-03

### Fixed

- Fixed various bugs affecting plugin functionality.
- Improved plugin stability and reliability.

### Improved

- Optimized breadcrumb updates and navigation.
- Improved overall plugin performance.
- Refined internal code structure for better maintainability.

## [1.0.3] - 2026-11-03

### Changed

- Updated README documentation.
- Improved plugin documentation and usage instructions.

## [1.0.2] - 2026-11-03

### Changed

- Updated plugin metadata for improved Acode Plugin Store compatibility.
- Added plugin icon, README, and changelog references.
- Improved plugin manifest information.

## [1.0.1] - 2026-11-03

### Fixed

- Fixed a critical bug that prevented the plugin from initializing correctly.
- Improved plugin initialization and startup reliability.

## [1.0.0] - 2026-11-03

### Added

- Initial release of Python Breadcrumbs.
- Added Python file navigation support.
- Added breadcrumb navigation for easier code navigation.
- Added automatic breadcrumb updates when switching between editor tabs.
- Added integration with the Acode editor interface.

### Improved

- Lightweight implementation for better editor performance.
- Clean and minimal interface.

### Fixed

- Addressed initial release bugs and stability issues.

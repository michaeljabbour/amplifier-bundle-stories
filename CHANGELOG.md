# Changelog

All notable changes to the amplifier-stories bundle will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-01-18

### Added
- Multi-format storytelling support (HTML, PowerPoint, Excel, Word, PDF)
- Integration with Anthropic skills library (pptx, xlsx, docx, pdf)
- Professional PowerPoint template based on Surface-Presentation.pptx
- Organized workspace structure for each output format
- Auto-open functionality for all generated files
- Comprehensive README with usage examples and dependencies
- Tools directory with session analysis utilities
- PowerPoint template specification with Microsoft corporate design
- File organization rules for each format
- Complete dependency documentation

### Changed
- Extended storyteller agent from HTML-only to 5 output formats
- Simplified PowerPoint workflow to use reusable template specification
- Updated .gitignore with comprehensive patterns for all workspaces
- Improved file organization with format-specific directories

### Fixed
- PowerPoint quality issues by requiring template adherence
- File organization - now uses proper workspace directories
- Missing gitignore patterns for Python cache and data files

## [0.1.0] - Initial Release

### Added
- Initial storyteller agent for HTML presentations
- "Useful Apple Keynote" style HTML decks
- SharePoint deployment script
- GitHub Pages hosting support
- Collection of existing presentation decks

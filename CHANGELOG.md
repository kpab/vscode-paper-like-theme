# Changelog

## [0.1.1] - 2026-07-28

### Fixed
- Whitespace dots (`editor.renderWhitespace`) were invisible: the color was identical to the selection background, so dots never showed while selecting text
- Terminal ANSI white / bright white were unreadable against the paper background (bright white was the exact background color)

## [0.1.0] - 2026-07-22

### Added
- Paper-toned colors for the full workbench UI: terminal (including ANSI palette), lists, inputs, buttons, find/suggest/hover widgets, peek view, notifications, quick input, menus, git decorations, and diff editor
- Semantic highlighting support (`semanticHighlighting` + `semanticTokenColors`) so LSP-based highlighting matches the theme
- Token colors for HTML/JSX tags and attributes, language constants, built-in functions, regex, escape sequences, JSON keys, Markdown, and invalid code
- Faded-ink accent colors: muted green for strings, faded blue for types

### Changed
- Darkened comments and line numbers for better contrast on the paper background

## [0.0.1]

- Initial release

# Changelog

## [0.1.2] - 2026-08-29

### Added
- Paper-toned bracket pair colorization and bracket pair guides (previously showed VS Code's default bright blue/green/purple)
- Notebook (Jupyter) UI colors: cell borders, focused/selected cells, output containers, and execution status icons
- Colors for inlay hints, inline suggestion ghost text, selection/hover/range highlights, and folded-region background
- Merge conflict block colors (current/incoming/common) in ink tones
- Terminal command decoration colors (shell integration marks)
- Ink-palette colors for suggest/outline symbol icons

### Changed
- Symbolic operators (`=`, `+`, `=>`, ...) are no longer bold brown; word-like operators (`new`, `typeof`, `instanceof`, `sizeof`, C++ casts, `and`/`or`/`not` in Python/Lua/Perl/SCSS/CSS, Swift `as`/`is`, ...) keep the bold keyword style. Ruby, PHP, and CoffeeScript word logicals share a TextMate scope with `&&`/`||` and become regular weight as well

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

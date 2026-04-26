# Change Log

All notable changes to the "ethereal" extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Released]

## [0.2.0] - 2026-04-26

### Added

- Comprehensive UI coverage for modern VS Code surfaces: rainbow brackets, bracket pair guides, inlay hints, sticky scroll, ghost text (Copilot), command center, banner, profile badge, quick input, keybinding labels, debug icons + console, notebook (Jupyter), testing (icons + coverage), chat / inline chat (Copilot), toolbar, symbol icons, charts, terminal command decorations, multi-diff editor, welcome page, settings UI, extension marketplace
- Markdown personality: bold styling on headings, distinct color treatment for bold (warm honey) vs italic (cool starlight), bold-italic, strikethrough, list markers, blockquote markers, inline code, code fence language tag, link text vs URL vs reference, horizontal rule, tables, task list checkboxes
- HTML coverage: tag punctuation, doctype, entities, JSX components (distinct from HTML tags), JSX expression braces
- CSS / SCSS / LESS coverage: element vs class vs ID vs pseudo selectors, properties, values, custom properties, at-rules, `!important`, units
- JSON, YAML, TypeScript decorators, Python self / decorators / f-strings, Rust macros, Go receiver, shell variable expansion, regex groups + character classes
- Tuned terminal ANSI palette to match the syntax colors

### Changed

- Editor background shifted from `#210b20` (eggplant) to `#181028` (twilight indigo) for a cooler, more celestial feel
- Unified syntax palette — removed leftover Material Theme legacy colors and remapped everything to a coherent ethereal palette: aurora violet, starlight blue, aurora mint, dusty rose, honey gold, twilight teal, rose quartz pink, misty mauve
- Softened UI text — primary foreground from `#d8d4e4` to `#c5bdd6`, muted from `#a89cc8` to `#9089b0`, with a subtle violet tint throughout
- Replaced loud, off-brand UI accents (magenta status bar, blue activity bar badge, brown filter widget, blue notification header, teal remote indicator, hot magenta editor group border, orange find highlight) with a constrained palette drawn from the syntax colors
- Defined a surface contrast hierarchy so selection stays visible across editor, popups, peek views, marker navigation, hover widgets, and suggest widgets
- Tuned text selection to `#4a2c70` so it's clearly visible on lighter widget backgrounds

### Fixed

- Fenced code block content no longer renders as nearly-invisible transparent black — code blocks now show readable text
- Show Problem popup text selection is now visible — `editorMarkerNavigation.background` and selection contrast were re-balanced
- Renamed theme file to lowercase `ethereal-color-theme.json` to match the path in `package.json` (was previously broken on case-sensitive filesystems)

## [0.1.0] - 2024-08-18

### Added

- Better syntax highlighting for all languages
- Better contrast for better readability
- Better color scheme for the theme

## [0.0.17] - 2024-04-25

### Changed

- Minor improvements to the theme


## [Unreleased]

## [0.0.16] - 2024-04-25

### Changed

- Made dull colors more vibrant

## [0.0.14] - 2024-04-20

### Changed

- Updated the editor background, activity bar, title bar, and side bar backgrounds to suit the theme better
- 

## [0.0.13] - 2024-04-15

### Changed

- Updated the editor foreground color to be more readable


<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# jetbrains-one-light-theme Changelog

## [Unreleased]

## [1.3.0]
### Added
- Dark theme variants: One Light Dark and One Light Dark Islands
- Complete dark color palette matching Atom One Dark scheme
- Dark syntax highlighting for all supported languages (Bash, C/C++, C#, Docker, Go, Groovy, Java, JavaScript, JSX, JSON, Jupyter, Kotlin, Log, Logcat, Markdown, PHP, Python, Regex, Ruby, Rust, SQL, TOML, SCSS/LESS, TypeScript, XML, YAML)
- Dark UI theming for Classic and Islands styles
- Islands Dark parent theme integration with proper panel color separation

### Fixed
- Go package qualifier highlighting (config., logger., slog., etc.) now displays in neutral color instead of string green

## [1.2.0]
### Added
- Expanded Python syntax highlighting (24 attributes: classes, functions, docstrings, f-strings, type hints, parameters)
- C/C++ syntax highlighting for CLion (21 attributes: macros, templates, structs, namespaces)
- PHP syntax highlighting for PhpStorm (15 attributes: classes, variables, heredocs, doc tags)
- Ruby syntax highlighting for RubyMine (21 attributes: symbols, instance variables, heredocs, regex, interpolation)
- C# syntax highlighting for Rider (19 attributes: ReSharper identifiers for classes, methods, properties, events)

## [1.1.0]
### Added
- Syntax highlighting for Bash/Shell, Rust, Docker, TOML, SQL, Groovy
- Expanded JavaScript, TypeScript, Java, Kotlin, Go syntax coverage
- JSX, SCSS/LESS support for WebStorm
- Markdown extended headers (level 5-6), bold, italic, table separator
- Jupyter notebook cell colors
- Log/Logcat output colors
- Inline parameter hint highlighting (current, highlighted)
- CSV column coloring (9 distinct colors)
- Diff inline inserted/deleted markers
- Islands UI theme variant (One Light Islands)
- ScrollBar and Separator UI styling

### Changed
- Normalized all color values with `#` prefix for consistency

## [1.0.2]
### Changed
- Updated README features list

## [1.0.1]
### Added
- Added plugin icon

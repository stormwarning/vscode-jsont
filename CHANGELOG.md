# Change Log
All notable changes to the extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).


## 0.3.1 - 2017-04-07
### Added
- `.conf` and `.preset` filetypes now assigned JSON language mode.


## 0.3.0 - 2017-03-12
### Added
- Line comment start & end to “block comment” entry in `language-configuration.json`; since proper block comments aren’t working anyway, and the configuration doesn’t allow for line comments to have an “end” character.
- Better patterns for objects & properties.
- Patterns for date constants & integers.
- Patterns for bitwise & comparison operators.

### Changed
- Restructured pattern repository to (hopefully) make updates a bit easier.


## 0.2.0 - 2017-02-25
### Added
- Highlighting maintained — mostly — within HTML metablocks (_eg_: within element atributes).

### Changed
- Simplified directives highlighting, particularly around predicates.

### Removed
- Block comments with `{##BEGIN}` and `{##END}` — seems to break or override other patterns. Will work on re-enabling, but for now only line comments are highlighted.


## 0.1.1 - 2017-02-22
### Added
- Extension image


## 0.1.0 - 2017-02-21
### Initial port release

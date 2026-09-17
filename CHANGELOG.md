# Changelog

All notable changes to devlog are documented here.
Format loosely follows [Keep a Changelog](https://keepachangelog.com/).

## [0.2.1] - 2026-05

### Added
- `--since` / `--until` flags for `export` to filter by date range
- Shell completion scripts for bash, zsh, and fish (`devlog completion <shell>`)
- Basic CI workflow

### Fixed
- Crash on empty journal entry
- Stale lockfile left behind when interrupted mid-write
- Date parsing for ISO week formats
- Unicode handling on Windows terminals
- Config file permissions (now `0600`)

## [0.2.0] - 2026-03

### Added
- `export` command with markdown and JSON output
- Tag filtering in `list`
- `config.toml` support under `~/.config/devlog/`

### Changed
- Journal I/O extracted into a dedicated module
- Entry timestamp logic simplified

## [0.1.0] - 2026-02

- Initial release: minimal CLI for developer notes and journaling

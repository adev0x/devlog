# devlog

Minimal CLI for developer notes and journaling from the terminal.

## Install

```bash
pip install -e .
```

## Usage

```bash
# Add a note
devlog add "fixed the timezone bug in the parser"

# Add with tags
devlog add -t bug -t python "off-by-one in date calculation"

# List recent notes
devlog list
devlog list -n 20
devlog list --tag bug

# Search
devlog search "timezone"

# View all tags
devlog tags

# Edit a note (opens $EDITOR)
devlog edit a1b2c3d4

# Delete
devlog delete a1b2c3d4

# Export as JSON
devlog export
devlog export -o backup.json
```

## Storage

Notes are stored as JSON in `~/.devlog/notes.json`. Override with `--dir`.

## License

MIT

<!-- reflection (2026-04-01) -->


<!-- log entry 1 (2026-04-01) -->


<!-- checkpoint (2026-04-01) -->


<!-- todo update (2026-04-06) -->


<!-- daily notes (2026-04-06) -->


<!-- update journal (2026-04-06) -->


<!-- checkpoint (2026-04-06) -->


<!-- session log (2026-04-06) -->


<!-- update journal (2026-04-15) -->


<!-- checkpoint (2026-04-27) -->


<!-- todo update (2026-04-27) -->


<!-- daily notes (2026-04-27) -->


<!-- log entry 2 (2026-04-27) -->


<!-- checkpoint (2026-04-27) -->


<!-- log entry 3 (2026-04-27) -->


<!-- daily notes (2026-04-27) -->


<!-- checkpoint (2026-05-14) -->


<!-- session log (2026-05-15) -->


<!-- session log (2026-05-15) -->


<!-- daily notes (2026-05-15) -->


<!-- log entry 4 (2026-05-16) -->


<!-- session log (2026-05-23) -->


<!-- todo update (2026-06-03) -->


<!-- log entry 5 (2026-06-03) -->


<!-- session log (2026-06-03) -->


<!-- todo update (2026-06-03) -->


<!-- reflection (2026-06-16) -->


<!-- todo update (2026-06-16) -->


<!-- reflection (2026-06-16) -->


<!-- session log (2026-06-16) -->


<!-- todo update (2026-06-20) -->


<!-- session log (2026-06-20) -->


<!-- session log (2026-06-21) -->


<!-- daily notes (2026-06-21) -->


<!-- update journal (2026-06-21) -->


<!-- checkpoint (2026-06-21) -->


<!-- session log (2026-06-21) -->


<!-- update journal (2026-06-27) -->


<!-- checkpoint (2026-06-27) -->


<!-- session log (2026-07-03) -->


<!-- checkpoint (2026-07-03) -->


<!-- daily notes (2026-03-08) -->


<!-- log entry 6 (2026-03-08) -->


<!-- daily notes (2026-03-16) -->


<!-- checkpoint (2026-03-16) -->


<!-- daily notes (2026-03-18) -->


<!-- quick log (2026-03-06) -->


<!-- daily notes (2026-03-06) -->


<!-- session log (2026-03-07) -->


<!-- checkpoint (2026-03-08) -->


<!-- quick log (2026-03-08) -->


<!-- reflection (2026-03-08) -->


<!-- update journal (2026-03-08) -->


<!-- session log (2026-03-08) -->


<!-- log entry 7 (2026-03-10) -->


<!-- update journal (2026-03-16) -->


<!-- daily notes (2026-03-16) -->


<!-- session log (2026-03-16) -->


<!-- session log (2026-03-18) -->


<!-- todo update (2026-03-18) -->


<!-- checkpoint (2026-03-18) -->


<!-- reflection (2026-03-20) -->


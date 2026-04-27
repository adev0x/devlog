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


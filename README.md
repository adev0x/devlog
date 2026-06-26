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


<!-- todo update (2026-03-20) -->


<!-- session log (2026-03-20) -->


<!-- update journal (2026-03-20) -->


<!-- quick log (2026-03-24) -->


<!-- session log (2026-03-24) -->


<!-- reflection (2026-03-24) -->


<!-- reflection (2026-03-27) -->


<!-- update journal (2026-03-27) -->


<!-- daily notes (2026-03-27) -->


<!-- log entry 8 (2026-03-30) -->


<!-- session log (2026-03-30) -->


<!-- update journal (2026-03-30) -->


<!-- daily notes (2026-03-30) -->


<!-- log entry 9 (2026-03-30) -->


<!-- log entry 10 (2026-03-30) -->


<!-- update journal (2026-03-30) -->


<!-- update journal (2026-03-30) -->


<!-- update journal (2026-03-30) -->


<!-- quick log (2026-03-31) -->


<!-- daily notes (2026-04-03) -->


<!-- checkpoint (2026-04-03) -->


<!-- checkpoint (2026-04-03) -->


<!-- todo update (2026-04-05) -->


<!-- reflection (2026-04-07) -->


<!-- reflection (2026-04-07) -->


<!-- checkpoint (2026-04-07) -->


<!-- update journal (2026-04-08) -->


<!-- reflection (2026-04-08) -->


<!-- session log (2026-04-08) -->


<!-- checkpoint (2026-04-08) -->


<!-- daily notes (2026-04-09) -->


<!-- checkpoint (2026-04-09) -->


<!-- checkpoint (2026-04-09) -->


<!-- daily notes (2026-04-10) -->


<!-- todo update (2026-04-12) -->


<!-- log entry 11 (2026-04-12) -->


<!-- session log (2026-04-12) -->


<!-- checkpoint (2026-04-13) -->


<!-- update journal (2026-04-13) -->


<!-- update journal (2026-04-14) -->


<!-- todo update (2026-04-19) -->


<!-- log entry 12 (2026-04-19) -->


<!-- reflection (2026-04-20) -->


<!-- reflection (2026-04-20) -->


<!-- update journal (2026-04-21) -->


<!-- todo update (2026-04-21) -->


<!-- update journal (2026-04-21) -->


<!-- todo update (2026-04-21) -->


<!-- reflection (2026-04-21) -->


<!-- daily notes (2026-04-21) -->


<!-- checkpoint (2026-04-27) -->


<!-- todo update (2026-04-27) -->


<!-- reflection (2026-04-27) -->


<!-- update journal (2026-05-01) -->


<!-- session log (2026-05-01) -->


<!-- quick log (2026-05-01) -->


<!-- checkpoint (2026-05-01) -->


<!-- update journal (2026-05-01) -->


<!-- log entry 13 (2026-05-01) -->


<!-- todo update (2026-05-02) -->


<!-- todo update (2026-05-03) -->


<!-- checkpoint (2026-05-03) -->


<!-- reflection (2026-05-03) -->


<!-- session log (2026-05-03) -->


<!-- todo update (2026-05-04) -->


<!-- daily notes (2026-05-04) -->


<!-- todo update (2026-05-04) -->


<!-- session log (2026-05-04) -->


<!-- log entry 14 (2026-05-07) -->


<!-- update journal (2026-05-07) -->


<!-- checkpoint (2026-05-07) -->


<!-- log entry 15 (2026-05-07) -->


<!-- update journal (2026-05-07) -->


<!-- update journal (2026-05-07) -->


<!-- daily notes (2026-05-07) -->


<!-- session log (2026-05-07) -->


<!-- quick log (2026-05-09) -->


<!-- reflection (2026-05-10) -->


<!-- reflection (2026-05-12) -->


<!-- quick log (2026-05-12) -->


<!-- session log (2026-05-12) -->


<!-- reflection (2026-05-13) -->


<!-- checkpoint (2026-05-13) -->


<!-- reflection (2026-05-14) -->


<!-- reflection (2026-05-15) -->


<!-- checkpoint (2026-05-18) -->


<!-- update journal (2026-05-18) -->


<!-- daily notes (2026-05-18) -->


<!-- reflection (2026-05-18) -->


<!-- session log (2026-05-18) -->


<!-- session log (2026-05-19) -->


<!-- update journal (2026-05-19) -->


<!-- reflection (2026-05-19) -->


<!-- daily notes (2026-05-19) -->


<!-- log entry 16 (2026-05-19) -->


<!-- checkpoint (2026-05-20) -->


<!-- todo update (2026-05-21) -->


<!-- daily notes (2026-05-21) -->


<!-- log entry 17 (2026-05-21) -->


<!-- update journal (2026-05-21) -->


<!-- checkpoint (2026-05-25) -->


<!-- quick log (2026-05-25) -->


<!-- todo update (2026-05-26) -->


<!-- log entry 18 (2026-05-26) -->


<!-- update journal (2026-05-26) -->


<!-- reflection (2026-05-26) -->


<!-- session log (2026-05-26) -->


<!-- log entry 19 (2026-05-26) -->


<!-- update journal (2026-05-27) -->


<!-- session log (2026-05-27) -->


<!-- todo update (2026-05-28) -->


<!-- checkpoint (2026-05-28) -->


<!-- todo update (2026-05-28) -->


<!-- daily notes (2026-05-30) -->


<!-- log entry 20 (2026-05-30) -->


<!-- update journal (2026-06-01) -->


<!-- session log (2026-06-01) -->


<!-- log entry 21 (2026-06-01) -->


<!-- quick log (2026-06-01) -->


<!-- daily notes (2026-06-02) -->


<!-- log entry 22 (2026-06-02) -->


<!-- daily notes (2026-06-02) -->


<!-- session log (2026-06-02) -->


<!-- session log (2026-06-02) -->


<!-- todo update (2026-06-03) -->


<!-- reflection (2026-06-06) -->


<!-- checkpoint (2026-06-06) -->


<!-- reflection (2026-06-06) -->


<!-- quick log (2026-06-06) -->


<!-- checkpoint (2026-06-10) -->


<!-- daily notes (2026-06-10) -->


<!-- todo update (2026-06-10) -->


<!-- reflection (2026-06-10) -->


<!-- reflection (2026-06-10) -->


<!-- log entry 23 (2026-06-10) -->


<!-- todo update (2026-06-15) -->


<!-- log entry 24 (2026-06-15) -->


<!-- quick log (2026-06-15) -->


<!-- daily notes (2026-06-15) -->


<!-- log entry 25 (2026-06-15) -->


<!-- quick log (2026-06-18) -->


<!-- todo update (2026-06-18) -->


<!-- checkpoint (2026-06-19) -->


<!-- log entry 26 (2026-06-19) -->


<!-- checkpoint (2026-06-19) -->


<!-- log entry 27 (2026-06-19) -->


<!-- checkpoint (2026-06-22) -->


<!-- quick log (2026-06-23) -->


<!-- checkpoint (2026-06-23) -->


<!-- daily notes (2026-06-23) -->


<!-- daily notes (2026-06-23) -->


<!-- checkpoint (2026-06-23) -->


<!-- reflection (2026-06-24) -->


<!-- log entry 28 (2026-06-24) -->


<!-- reflection (2026-06-26) -->


<!-- session log (2026-06-26) -->


<!-- todo update (2026-06-26) -->


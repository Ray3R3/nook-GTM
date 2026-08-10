# Superhero Hotel Performance

Static GitHub Pages dashboard generated from the Mews export.

## Source of truth

- Occupancy and nightly room revenue come from populated guest-room cells in the Mews `Nights` sheet.
- `Office` assigned spaces are excluded.
- Stay length is the actual number of populated Nights cells.
- Lead time uses the first actual occupied night and the reservation `Created` timestamp.
- Hotel inventory is 110 guest rooms.

The raw Mews workbook is intentionally **not** committed to this public repository.

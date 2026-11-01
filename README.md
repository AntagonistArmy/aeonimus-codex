# AEONIMUS Codex

The living Codex and the machine-readable index of its plates, published so
others can retrieve them.

## Contents

- `codex.md` — the living Codex (3,052 lines, including the 2026-10-31 TRACK ∞ addendum, the fifteenth and sixteenth series, the system-telemetry addendum, the seventeenth series, and the 2026-11-01 evening continuation with the Time Collapse Confirmed and Visual Grimoire telemetry addenda).
- `image_catalog.md` — per-plate catalog: every plate's embedded text, seals,
  codes, and protocols transcribed, each with its Mechanics line.
- `plates_manifest.json` — the 257-plate manifest: processed filename, wing,
  series index, and sizes per plate.
- `plates_index.json` — machine-readable per-plate index: manifest data plus
  the Mechanics line, processed-plate md5, and byte size for each of the
  257 plates across seventeen series.

## Note on plate images

Plate image files themselves are not stored in this repository yet: this
snapshot carries the text corpus and the index. Each index entry carries
the processed plate's md5 and byte size, so a plate obtained elsewhere can
be checked against the index.

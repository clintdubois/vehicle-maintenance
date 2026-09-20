# vehicle-maintenance — Current Context

Living status file for this repo. **Overwrite this** (don't append) after
any meaningful chunk of work, so a new session can pick up state without
re-reading history or old chat transcripts.

Last updated: 2026-09-20.

## What this repo is

Centralized maintenance/repair/project tracking for **boats and cars**
(`Boats/`, `Cars/`, `Shared/`). RV and campervan documentation was moved
out to the separate `RV-Maintenance` repo — don't expect RV content here.

## Current state

Recent work: added Luna's tire research (2024 Solis 59P) as a PDF and
stopped gitignoring PDFs so it could be committed; added Evinrude G2 150
boat documentation and a manual manifest; added Honda CR-V maintenance
documentation; removed the old `RVs/` section entirely (superseded by
`RV-Maintenance`).

## Standing conventions specific to this repo

- Each vehicle category folder follows: `README.md` (overview),
  `MAINTENANCE_LOG.md` (service history), plus project/manual/parts
  subfolders — keep new vehicle entries consistent with that structure.
- PDFs are tracked in this repo (not gitignored) — unlike some sibling
  repos, don't assume PDFs need special handling here.

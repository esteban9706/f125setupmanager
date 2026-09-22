# F1 25 Setup Manager

A single-page reference tool for browsing F1 25 (2026 season) car setups by track, with dry/wet condition filtering.

**Live site:** https://esteban9706.github.io/f125setupmanager/

## Features

- 134 community setups across all 24 tracks
- Filter setups by Dry, Wet, or All conditions
- Qualifying, race, and balanced setup variants per track
- Hot lap video links per track
- Search by track or setup name

## Files

- `f1_setup_manager_v2.html` — the current app (open this or visit the live site)
- `F1_25_Setups.json` — raw setup data source
- `f1_setup_manager.html`, `f1_setup_manager_full.html` — earlier versions, kept for reference

## Running locally

```bash
npx http-server -p 8000 -c-1
```

Then open `http://localhost:8000/f1_setup_manager_v2.html`.

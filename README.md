# Pictos Tracker

A lightweight, single-page web tracker for **Clair Obscur: Expedition 33** — keep tabs on which Pictos you've collected across your playthrough.

**Live site:** https://odine1980.github.io/Pictos/

---

## Features

- **210 Pictos** total — 193 base game + 17 DLC (Thank You Update)
- **2 Missable Pictos** flagged with warnings so you don't lock yourself out
- **Progress tracking** — collected / total / remaining counts with a visual progress bar
- **Search** by Pictos name or location
- **Filters** — All, Missing, Collected, Missable, DLC
- **Sticky letter headers** (A–Z) for quick navigation through the base game list
- **localStorage persistence** — your progress auto-saves in-browser
- **Export / Import** — backup and restore your collection as JSON
- **Dark theme** styled to match the game's aesthetic

---

## Missable Pictos

| Pictos | Location | Condition |
|--------|----------|-----------|
| **Exposing Attack** | Flying Waters — Noco's Hut | Must buy from Noco (3,600 Chroma, fight required). Gone after leaving the area. |
| **Auto Powerful** | Floating Cemetery | Defeat Chalier Nevron **and** agree to fulfill their final wish. |

> No achievement exists for collecting all Pictos, but completionists beware — these two can be permanently missed.

---

## Data Sources

- [Fextralife Wiki — Pictos](https://expedition33.wiki.fextralife.com/Pictos)
- [Game Checklists — All Pictos](https://game-checklists.com/expedition33/all-pictos.html)

---

## Version History

| Version | Date | Notes |
|---------|------|-------|
| **v0.4** | 2026-06-08 | Reordered sections: Base Game → DLC → Missable. Added README. |
| v0.3 | 2026-06-08 | Refactored base game list to single continuous scroll with sticky A–Z headers. |
| v0.2 | 2026-06-08 | Initial styling, filters, search, export/import. |
| v0.1 | 2026-06-08 | Initial release with full pictos dataset. |

---

## Tech Stack

- Pure HTML / CSS / JavaScript — no build step, no dependencies
- Hosted on **GitHub Pages**

---

## License

Personal project — feel free to fork and modify for your own tracking needs.

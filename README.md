# PGCN Climacrossword

**Create | Initiate | Innovate | Leaving No One Behind**

A self-contained, browser-based interlocking climate crossword developed by the Peace, Gender and Climate Network (PGCN) as a pilot educational tool for climate literacy.

---

## About

Climacrossword is a single-file HTML application requiring no installation, server, or internet connection once loaded. It is built around a **Know → Understand → Connect → Act** learning architecture: solving a clue does not simply score a point, it surfaces a plain-language explanation of the term and a Climate Action Insight connecting it to real-world response.

The word bank is intentionally **universal**, not location-specific, consistent with PGCN's decision for its companion tool, PGCN Climapuzzle, so the game is usable by a worldwide audience rather than tied to any single national curriculum.

---

## Features

- **Genuine interlocking crossword** — words share letters and cross each other, generated fresh on every puzzle, not a simplified word list
- **24-word bank across six categories** — Climate Science, Climate Impacts, Mitigation, Adaptation, Climate Action, and Climate Justice, four words each
- **Randomised word selection** — each New Puzzle randomly draws 2 of the 4 words per category (12 total), so both the clues and the grid layout vary between rounds, not the layout alone
- **Learning Card on every correct answer** — shows a plain-language explanation and a Climate Action Insight tied to that term
- **Standard crossword interaction** — click a clue to highlight and jump to it, type to auto-advance, arrow keys to navigate, backspace to move back
- **Earth Gaming Standards International (EGSI) Pilot Scoring Metric**
  - Points weighted by word count, a time bonus for finishing under par, and a hint penalty
  - Performance tiers (Entry, Bronze, Silver, Gold)
  - A screenshot-ready Performance Record card for informal score verification
- **PGCN institutional branding** embedded directly in the file (header mark, watermark, and result card mark)
- **Responsive layout**, tested to remain legible on typical mobile screens

---

## Running the Game

No build step or dependencies are required.

1. Download `index.html` (or `PGCN_Climacrossword.html`)
2. Open it directly in any modern browser (Chrome, Firefox, Safari, Edge)

To host it as a public webpage via GitHub Pages :-

1. Upload the file to this repository, named `index.html`
2. In repository **Settings → Pages**, set the source branch to `main` and the folder to `/ (root)`
3. GitHub will publish a public URL for the game

---

## How It Works

On each New Puzzle, the game randomly samples 2 words from every category (12 words total), then generates a crossword layout by placing the longest word first and greedily intersecting each subsequent word against letters already on the grid, retrying up to 250 times per generation and keeping the most compact successful layout. This has been stress-tested at 100% placement reliability across 40 independent runs, with grid size consistently held between 15 and 19 cells for mobile legibility, and confirmed to produce genuinely distinct word combinations round to round.

---

## Project Status

This is a **pilot build**, a companion product to PGCN Climapuzzle. Before any coordinated public launch, the following institutional checks are required, as documented in the internal `PGCN Pre-Launch Governance and Ethics Checklist` :-

- Safeguarding review of the optional player name field and screenshot submission channel, particularly given anticipated use by learners under eighteen
- Cross-device and low-bandwidth performance verification
- Consistent EGSI positioning as a PGCN pilot scoring methodology, not an external certifying body
- Accessibility review (colour-independent category coding, keyboard navigation)

The EGSI Performance Record card explicitly states it is a performance record and not a certificate.

---

## Roadmap

Potential next-phase additions :-

1. Expanded word bank beyond the current 24 entries
2. Accessibility improvements (colour-independent category indicators, screen-reader support)
3. Optional difficulty tiers, mirroring PGCN Climapuzzle's Easy / Medium / Hard structure

---

## Institutional Context

Climacrossword is a flagship digital learning product of the Peace, Gender and Climate Network, sitting alongside PGCN Climapuzzle, RUZIVO, ClimateSense 21, Game of 55, and Geobot AI within PGCN's broader digital education portfolio.

---

## License and Use

This tool is developed for institutional, educational, and outreach use by PGCN. For questions regarding use, distribution, or partnership, contact PGCN directly.

---

**Peace, Gender and Climate Network**
Research | Policy | Systems Integration

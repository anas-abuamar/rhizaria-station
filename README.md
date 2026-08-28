# Rhizaria Station

**Boothbay Radiolaria Program — the submerged build.** Revision D, 20 Aug 2026.

A single self-contained web page describing a ~$1000 in-situ plankton imager
designed to be moored under a floating dock in East Boothbay, Maine, and to
photograph living Rhizaria — acantharians and polycystines, 50–200 µm — where
they live, since nets destroy them.

Open `index.html` in any browser. No build step, no server, no dependencies to
install.

## What's on the page

- **An interactive 3D model** of the site, instrument, flowcell and dock box,
  with a tide slider that shows depth staying fixed at 5.00 m while clearance
  over the bed drops to 1.56 m at low water.
- **The chain** — what happens to a single cell from intake to discharge.
- **The volume arithmetic** — 2.1 µL per frame, ~66 litres a year, and why
  sampled volume rather than optical resolution is the constraint that decides
  the project.
- **A risk register** of twelve unsettled engineering questions, each with how
  to settle it and what that costs. Three could stop the project (are the
  organisms there; do the optics resolve diagnostic features; how much of the
  channel is actually in focus).
- **The software plan** — on-instrument triage, EcoTaxa vignettes,
  MorphoCluster cold start, open-set thresholds, and why general biological
  foundation models are not going to rescue the classifier.
- **A full bill of materials** with per-part rationale, vendors and prices, plus
  interactive configuration toggles and a running cost total.
- **A time estimate** and the order to build things in.
- **Sources** — every published figure cited, every estimate marked.

Configuration ticks and toggles are saved in the browser's `localStorage` only.

## Honest state

Prices marked `~` are estimates of typical retail as of August 2026. Time
estimates are judgement, not measurement. The page's own closing section spells
out exactly which figures are verified from published sources and which are the
author's own calculations or guesses.

## Credits

Three.js r169 (MIT, © 2010–2024 three.js authors) is inlined in `index.html` so
the page works offline. Fonts load from Google Fonts when online and fall back
to system faces otherwise.

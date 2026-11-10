# Design

<!-- impeccable:design-schema 1 -->

## World

Data field, after Ryoji Ikeda's datamatics: pure black and pure white, monospace numerics at data density, hairline rules, a single sine curve, barcode bar fields. Locked by the user 2026-11-08 after live comparison against modern-minimal, cartographic, and transit directions (transit was built first and rejected; the fusion of minimal + data field was offered and the pure data field won).

## Palette

- Exactly two inks: `#000000` and `#FFFFFF`. No greys as palette members; hierarchy comes from opacity steps of the ink (0.75, 0.32, 0.18).
- No accent color. The theme inversion IS the accent: GitHub dark renders the black field, GitHub light renders the full-frame inverted white field, swapped automatically via `prefers-color-scheme` `<picture>`.

## Type

- Structure (headings, prose): GitHub's system sans stack.
- All data (records, metrics, stack items, labels): monospace, set in code spans on GitHub and `ui-monospace` stacks in authored SVGs; uppercase with letter-spacing in SVGs only (GitHub markdown cannot letter-space).

## Component language

- Record tables: three columns RECORD | SCALE | MECHANISM, data in mono code spans, hairline-ruled (GitHub table borders).
- Banner: authored SVG, 1200x500 — barcode field (thin register + bright register), one sine curve, name in mono capitals, right-side data columns, field-notes line.
- Live-data badges and per-tech icon badges: `flat-square`, all-black (`labelColor=000000&color=000000`), white simple-icons logos (`logoColor=white`); items without an icon ship as text-only black badges. Tech icons are data, not decoration: one badge per `main.tex` skill item, no additions.
- Contact as plain text links in one row. Snake animation kept at the bottom as the activity scan.
- Motion: none in v1. The inversion between themes is the single authored moment. If motion returns, it is one bounded SMIL effect, never scattered.

## Bans

Color badges, emoji as icons, illustration and metaphor devices, gradient fills, card grids, invented metrics. Every number traces to `resume-ops/resumes/main.tex`; pi-native facts trace to its repository; live counts render only through live badges.

## Reach

The field-record table, mono data styling, and black badge treatment extend to future surfaces (portfolio, docs) unchanged; the banner SVG system (dark/inverted pair) is the reusable signature asset.

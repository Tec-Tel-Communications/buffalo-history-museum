# Buffalo History Museum — Tec-Tel × Hanwha microsite

Standalone prospect microsite (same pattern as `jetro-aisle-safety`): a single
static `index.html` + one CSS file, hostable as a shareable link, for Robin
Foley at The Buffalo History Museum.

## What's here
- **`explainer.html`** — a self-contained animated in-page explainer of the
  phased Hanwha plan (Phase 1: Wisenet WAVE on existing Pelco cameras over
  ONVIF; Phase 2: Hanwha AI cameras add real-time alerts). No dependencies,
  autoplays, respects reduced-motion. Lift its `<section class="ttx-explainer">`
  + `<style>` + `<script>` into the page, or embed via `<iframe>`.

## For Claude Design (building the page)
Build the microsite in this repo (`index.html` + CSS). Leave a full-width
`<section id="explainer-slot">` near the top — the explainer above drops in
there. Also leave a **Phase 1 pricing** section as a slot; real numbers land
once the engineer (Teak) reviews scope and prices it.

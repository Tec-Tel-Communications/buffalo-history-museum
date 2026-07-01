# Buffalo History Museum — Tec-Tel × Hanwha microsite

Standalone prospect microsite for Robin Foley (The Buffalo History Museum):
software-first path off Pelco VideoXpert onto Hanwha Wisenet WAVE, phased so
the AI cameras land with the fall grant.

## Files
| File | What it is | Status |
|---|---|---|
| `explainer.html` | Self-contained animated in-page explainer of the 2-phase plan. Drops into the page's `#explainer-slot`. | Done |
| `pricing-section.html` | Drop-in **Phase 1 pricing** section. Line-item skeleton with placeholder `$ —` values — search `TEAK` for the spots that need his numbers + channel count. | Drafted, awaiting pricing |
| `design-snapshot.html` | Rendered snapshot exported from Claude Design. **Renders, but NOT clean source** (markup is JS-injected/escaped). Reference only. | Reference |

## To finish the build
1. **Get the clean dev-handoff source in here** — Claude Design's push-ready
   folder (`index.html` + `buffalo-hanwha.css` + `assets/` + `.nojekyll`).
   `design-snapshot.html` is the snapshot form and can't be cleanly edited.
2. Wire `explainer.html` into `#explainer-slot`.
3. Insert `pricing-section.html` before the closing CTA (`#book`); restyle to
   the site's own `.section` classes/tokens.
4. Drop Teak's Phase 1 numbers into the `data-price` spans.
5. Deploy to a live URL (Vercel / Pages) for review.

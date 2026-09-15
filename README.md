# SOS 110 Biomimicry Web Slideshow

A click-through web lecture, "Biomimicry: Innovation Inspired by Nature" (8 slides), built from the
*Biomimicry Resource Handbook* (D. Baumeister et al., Biomimicry 3.8, 2023). All content is paraphrased from that source.

## Contents
- `index.html` — the slideshow (open this). Self-contained: hand-drawn SVG interactives are inline;
  only Google Fonts and the embedded YouTube video (slide 7, CBS Sunday Morning) load from public URLs.
- `.nojekyll` — tells GitHub Pages to serve all files as-is

## Navigation
Arrow keys / space or the on-screen ‹ › buttons; ≡ opens the slide menu.

Source of truth: `_deck-builder/biomimicry.py` + `_deck-builder/biomimicry_parts/` (rebuild with
`DECK_OUT=…/biomimicry-web/index.html python3 biomimicry.py`).

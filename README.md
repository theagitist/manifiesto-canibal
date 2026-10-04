# Manifiesto Caníbal

An interactive web reading of Francis Picabia's *Manifeste cannibale dada* (1920). The manifesto devours itself as you scroll: words that pass the "mouth" line get digested, the *nada* litany empties the page, and the only line left standing is Picabia's promise to sell you his paintings in three months.

Made for a graduate seminar on cannibalism in Latin American literature (SPAN 550B, UBC) by Adri M.

All four pages are trilingual (Spanish, French, English); the language choice is shared across them.

## Pages

- `index.html` : the self-consuming manifesto. An optional sound toggle plays a grungy ambient bed that swells as you scroll toward the void.
- `presentacion/` : the thesis (Picabia's Dada cannibalism against Oswald de Andrade's anthropophagy) and the discussion questions. This is what an audience sees.
- `guion/` : the run of show, written as a **reproducible protocol** any facilitator can run, not a personal script. The reading is detailed (the manifesto's chain of equivalences, the litany of *nada*, the self-cannibal turn to the market, and the deliberate contrast with Oswald de Andrade, brought in from outside Picabia's text). Per-language PDFs (two-page script + a closing questions sheet) and a Print button.
- `compartir/` : a QR page for sharing the piece
- `poster.svg` : DADÁ / NADA poster used as the link card

## Built with

Plain HTML, CSS and vanilla JavaScript. No build step, no dependencies. Type is Anton, Spectral and Space Mono (Google Fonts); the scroll "consumption" effect uses IntersectionObserver, and the QR is inlined as SVG so the share page works offline. The guion PDFs are rendered from the live page with headless Chromium (`--no-pdf-header-footer`, one per language).

Live at https://polivoxia.ca/manifiesto_canibal/

## License

The original materials here (the pages, the guion, the handout, the texts) are licensed **CC BY-NC-SA 4.0** (attribution, non-commercial, share-alike): https://creativecommons.org/licenses/by-nc-sa/4.0/ . The seminar activity is meant to be reproduced and adapted under those terms. The quoted manifestos, the audio bed (a non-commercial s.29.21 remix), and the Google Fonts keep their own rights. See `LICENSE` for details.

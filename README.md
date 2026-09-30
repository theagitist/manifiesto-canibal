# Manifiesto Caníbal

An interactive web reading of Francis Picabia's *Manifeste cannibale dada* (1920). The manifesto devours itself as you scroll: words that pass the "mouth" line get digested, the *nada* litany empties the page, and the only line left standing is Picabia's promise to sell you his paintings in three months.

Made for a graduate seminar on cannibalism in Latin American literature (SPAN 550B, UBC) by Adri M.

## Pages

- `index.html` : the self-consuming manifesto, in Spanish, French and English
- `presentacion/` : thesis, run of show, and discussion questions
- `compartir/` : a QR page for sharing the piece
- `poster.svg` : DADÁ / NADA poster used as the link card

## Built with

Plain HTML, CSS and vanilla JavaScript. No build step, no dependencies. Type is Anton, Spectral and Space Mono (Google Fonts); the scroll "consumption" effect uses IntersectionObserver, and the QR is inlined as SVG so the share page works offline.

Live at https://polivoxia.ca/manifiesto_canibal/

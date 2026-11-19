# Personal homepage redirect

The personal homepage is maintained and served at https://sugrsertraline.top/.

The GitHub Pages entry point is https://sugrsertraline.github.io/. Keep this repository named `SugrSertraline.github.io` so GitHub publishes the user site at the root address.

This repository redirects both the root address and the former `/homepage/` address to the same personal homepage. It does not contain a second copy of the personal website or its assets. JavaScript preserves query parameters and section anchors; meta refresh and a normal link provide fallbacks.

GitHub Pages publishes `main` from `/`. Leave its custom-domain setting empty: `sugrsertraline.top` is served by its existing host, and the separate Neuink project site remains at https://sugrsertraline.github.io/neuink/.

The original page and assets remain recoverable in Git history (last full-page commit: d5954d1c5d6fb722486fb10d48ad14314860896f).

# ntddk.github.io

Personal CV of Yuma Kurogome — served at <https://ntddk.github.io/>.

A single self-contained `index.html` (no build step, no external assets). The
dark hero renders a **point-cloud portrait of my dog** (a black-and-tan
Pomeranian) on a `<canvas>`, with a **Conway's-Game-of-Life "wind"** rippling
through the fur along the silhouette — and wherever the cursor moves. The text
sits over the dog's body, with a soft scrim behind the column for readability.
The favicon (a circular point-cloud crop of the same dog) and every asset are
inlined as data URIs.

- `.nojekyll` makes GitHub Pages serve the file as-is.
- Fixed dark theme; respects `prefers-reduced-motion` (animation off).
- Canvas hidden on small screens and in print.

Edit `index.html` directly.

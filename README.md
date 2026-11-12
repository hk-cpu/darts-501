# The Oche: 501 darts tap scorer

Static, single-file web app (`index.html`, everything inline). Hosted on GitHub Pages.

* **Board**: tap where each dart landed. The double and treble rings are drawn about 4–5× wider than on a real board, so they're easy to hit, and the hit areas match the drawing exactly. *Big* / *Huge* ring sizes.
* **Clean taps only**: the dart is taken from where your finger went down. If you slide more than 12 px, use two fingers, or let the browser scroll, nothing scores. While your finger is down, a bubble shows what will score (e.g. `T20 · 60`).
* **Number pad**: tap the number (1–20), then Single / Double / Treble. There are also buttons for 25, Bull and Miss.
* **Score caller**: speaks every dart, what's left when you're on a finish, the turn total ("One hundred and eighty!"), and calls Bust and Game shot. You can turn it on or off with the Sound button.
* **Scoreboard on another phone**: scan a QR code to follow the score live on a second phone, which can also add or undo a dart.

The earlier camera auto-scoring build is kept in the dev folder's `camera-archive/` and is not shipped.

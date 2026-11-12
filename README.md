# The Oche: 501 darts tap scorer

Static, single-file web app (`index.html`, everything inline). Hosted on GitHub Pages.

* **Board**: tap where each dart landed. The double and treble rings are drawn about 4–5× wider than on a real board, so they're easy to hit, and the hit areas match the drawing exactly. *Big* / *Huge* ring sizes.
* **Clean taps only**: the dart is taken from where your finger went down. If you slide more than 12 px, use two fingers, or let the browser scroll, nothing scores. While your finger is down, a bubble shows what will score (e.g. `T20 · 60`).
* **Number pad**: tap the number (1–20), then Single / Double / Treble. There are also buttons for 25, Bull and Miss.
* **Score caller**: speaks every dart and what's left after every dart, the turn total ("One hundred and eighty!"), and calls Bust and Game shot. You can turn it on or off with the Sound button.
* **🎤 Voice scoring**: shout each dart ("treble twenty", "double sixteen", "bull", "outer bull", "miss", "undo", "next"), or switch to **Turn total** and say "scored sixty" or "one eighty". It shows what it heard with an Undo button and repeats it back. It copes with common mishears ("tribble", "double for", "ate"). The mic pauses while the phone is talking. It needs Chrome or Edge and an internet connection (the speech goes to the browser's speech service).
* **Finish advice**: after every dart it tells you what to aim at. On an odd number, or one that isn't a double, it gives a setup that leaves your best double, e.g. "Forty-three left. Single three, leaves double twenty". The screen lists alternatives ("Try 3, 11 or 7") and bust warnings ("Double one only, anything else busts"). Over 170 it suggests a scoring shot that leaves a finish.
* **Commentator**: the **Off / Hype / Hype + Roast / Savage** setting. It hypes treble twenties, tons, 180s and checkouts, roasts misses, single ones, busts and missed doubles, and pushes you on when you're close to a finish. It stays friendly and PG-13 and never comments on the person, only the darts.
* **One-screen phone layout**: while you play, the player and score, the 3 dart slots, the aim line, the board and Miss / Undo / 🎤 Voice all fit on one screen with no scrolling, even on a 360×640 phone. The board is sized from whichever is smaller, the space's width or its height. Board/Pad, ring size, Sound, voice mode, Commentator, Scoreboard on another phone and New match are under **⚙ Settings**. Finish advice and the scoreboard are collapsible sections below. On an unfolded Fold6 or in landscape, the board is on the left and the controls are on the right. The layout respects safe areas (100dvh, viewport-fit=cover).
* **Scoreboard on another phone**: scan a QR code to follow the score live on a second phone, which can also add or undo a dart.

The earlier camera auto-scoring build is kept in the dev folder's `camera-archive/` and is not shipped.

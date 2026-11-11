# The Oche: 501 darts scorer with camera assist

Static, single-file web app (`index.html`, everything inline, no CDNs or libraries). Host on GitHub Pages (HTTPS is needed for the camera).

* **Tap mode**: tap where each dart landed on the board diagram, or use the S/D/T + number picker.
* **Camera mode**: mount the phone facing the board, press *Start camera* and calibrate by tapping the outer double-ring edge at the top of 20, right of 6, bottom of 3 and left of 11. Each dart the camera sees shows up as a pending dart. Confirm it, fix it (tap the board or use the picker) or let it auto-confirm.

How detection works: frame differencing against the last still picture of the board, a ~0.5 s stillness gate, connected components, dart tip = blob end nearest the camera's foot point (estimated from the calibration homography), then mapped through the homography to the board model and scored.

Everything runs on the phone. No frames are uploaded.

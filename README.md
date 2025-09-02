# seconds-stopwatch

A super-tiny PWA stopwatch that counts whole seconds with a drift-free timer.

Usage
- Single big button cycles: Start → Stop → Reset
	- Start: begins counting
	- Stop: pauses and lets you Reset
	- Reset: sets the counter back to 0
- Add it to your home screen for one-tap access; works offline.

Notes
- Uses performance.now() for accurate elapsed time.
- Requests a screen wake lock while running (if supported).

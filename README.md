# Hospital Run

A Temple Run-style endless runner set in hospital hallways. It's made for nurses, as a gift.

**Play:** https://fosterdolling.github.io/hospital-run/ (works best on a phone; on iPhone use Share, then Add to Home Screen for full screen)

## How to play
- **Swipe left/right** to change lanes. At a junction, swipe toward a sign to turn the corner. Miss the turn and you hit the wall.
- **Swipe up** to jump (spilled bedpans, wet-floor signs, wheelchairs).
- **Swipe down** to slide (gurneys).
- On desktop, use the arrow keys or WASD. **P** pauses.

Mr. Henderson from Room 12 is chasing you. Stumble once and he catches up. Stumble again before he falls back and he's got you.

**Power-ups**
- Coffee: speed boost, and you plow through anything for 5 seconds.
- The 7 o'clock shift-change clock: Mr. Henderson becomes someone else's problem.

## Tech
A single `index.html` with Three.js from a CDN. There are no build steps or asset files. Everything is built from code: the merged low-poly geometry, canvas-drawn signs and the synthesized sound effects.

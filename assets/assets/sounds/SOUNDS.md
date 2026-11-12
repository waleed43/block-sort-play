# Block Sort sound effects

All clips in this folder are **original procedural audio** synthesised for
this game (see `tool/make_sounds.py`). No third-party samples were used.

| File       | Use                                      | Length |
|------------|------------------------------------------|--------|
| tap.wav    | Soft tap / pop when a truck is selected  | ~110 ms |
| hop.wav    | Block hop whoosh as a run arcs over      | ~280 ms |
| land.wav   | Soft landing tick at the end of a hop    | ~220 ms |
| lid.wav    | Lid closes over a finished truck + chime | ~480 ms |
| pour.wav   | Cubes rattle into the U tube             | ~700 ms |
| chime.wav  | Extra complete sparkle (kept)            | ~550 ms |
| stuck.wav  | Gentle error buzz when a hop is refused  | ~320 ms |
| truck.wav  | Kept from earlier versions (unused live) | ~950 ms |
| win.wav    | Warm rising win jingle                   | ~1.15 s |

Format: 44.1 kHz, 16-bit PCM mono WAV, faded and peak-normalised so they
do not clip. Volumes are balanced around a 0.72 peak. Seed: 20261113.

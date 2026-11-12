# Block Sort sound effects

All clips in this folder are **original procedural audio** synthesised for
this game (see `tool/make_sounds.py`). No third-party samples were used.

| File       | Use                          | Length |
|------------|------------------------------|--------|
| tap.wav    | Soft tap / pop when a box is picked | ~110 ms |
| land.wav   | Box landing on a rack or in holding | ~220 ms |
| chime.wav  | Rack filled, truck ready to leave   | ~550 ms |
| truck.wav  | Engine rumble + drive-off           | ~950 ms |
| stuck.wav  | Gentle error buzz when the dock jams | ~320 ms |
| win.wav    | Warm rising win jingle              | ~1.15 s |

Format: 44.1 kHz, 16-bit PCM mono WAV, faded and peak-normalised so they
do not clip. Volumes are balanced around a 0.72 peak (truck and stuck a
little softer in the source mix).

# Pocket Studio

A single-file music studio that runs in the browser — no install, no build step, nothing to serve.
Open `index.html` and play.

**[Open it here](https://YOUR-USERNAME.github.io/pocket-studio/)** — replace `YOUR-USERNAME` once GitHub Pages is on.

## What's inside

Three instruments, a composer and a recorder, all in one HTML file:

- **Synth** — three oscillators, a filter section (low/high/band pass, 12 or 24 dB, key tracking and its own envelope), amp envelope, LFO and detune. Chord presets by genre, a split keyboard, and an arpeggiator with music-box figures.
- **303** — monophonic acid bass: saw or square, resonant filter with env mod and decay, accent, slide, drive and an echo send.
- **808** — twelve drum voices synthesised from scratch (no samples), each with level, tune, decay and a tone control.
- **Composer** — piano-roll lanes for the synth and 303, a step grid for the drums, loop lengths of 1–8 bars, snap, undo and live recording of anything you play, including arpeggios.
- **Mix** — master volume, tempo-synced ping-pong echo and reverb.

## Songs

Songs are saved in the browser, and can be exported as `.m1p.json` files or as text "song codes".
The `songs/` folder holds example songs — download one, then in the app tap **SONG → OPEN FILE**.

A song file is a list of tracks, each with its own notes and its own sound, so it stays readable
and new instruments can be added without breaking older files.

## Audio export

**SONG → EXPORT AUDIO** renders the song offline through the same engine you hear and saves a
16-bit 44.1 kHz WAV — the whole mix, or one instrument on its own as a stem.

## Browser support

Built on the Web Audio API; works in current Chrome, Safari, Firefox and Edge, on phones and desktop.
Audio starts on your first tap, as browsers require.

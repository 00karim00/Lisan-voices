# lisan-voices

Voice packs for the **Lisan (لسان)** language-learning app.

- `fa/` — Ganji natural Persian voice (word and sentence recordings, Ogg Opus bundles).
- `fa/manifest.json` — bundle names and byte sizes, used by the app to download and verify.

The app downloads these files on demand from inside the app.

## Voices
- `fa/ganji/`, `fa/amir/`, `fa/gyro/`, `fa/reza/` — each has the recording bundles (`*.bin`), offsets (`bo.json`), sizes (`manifest.json`) and a short `sample.ogg`.
- `fa/voices.json` — the list the app uses.
- The `fa/*.bin` files at the top level are kept for app version 4.9.

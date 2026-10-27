# Drone

A shruti-box style drone to practice against. Pick a key, mix in whichever voices you want, and play along.

**Use it:** https://mgilvryallen.github.io/drone/

- **Just intonation:** every voice is a whole-number ratio of the root (fifth 3:2, fourth 4:3, octaves 2:1 and so on), so it rings clean instead of equal-tempered.
- **Presets** to start from: Front Porch, Cross A (for AEAE), Sawmill (modal G), Pipe Drones, Modal E, Om (136.1 Hz), Singing Bowl and Deep Rest. It opens on Front Porch the first time.
- **Save your own presets:** tap **save as preset** and give it a name. Tap one of yours to **rename** or **delete** it.
- **Ten voices**, each with its own level slider: low root, low 4th, root, 4th, 5th, 6th, ♭7th, octave, 9th and 10th. **reset levels** puts them back where they started.
- **Mingle:** now and then, a voice strays, and finds its way back.
- **Fine tune** up or down by single cents (±50). The slider catches on A = 432, 435, 440, 442, 443 and 444.
- **Tone** runs from dark to bright (and airier). **Breath** runs from still to shimmering: the reeds beat against each other more.
- Open it with a key already set: `mgilvryallen.github.io/drone/#key=A` (Tunes uses this).

## Put it on your phone

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open it in Chrome, tap the menu, then **Install app**.

The screen stays on while it plays. Switch apps or lock your phone and the drone stops, on purpose: put the phone down and listen.

## Sync your presets (optional)

Turn on **Sync** to have your saved presets on your phone and computer. It works the same way as Gas, and the same GitHub token works for both: in Gas, tap **copy token for another device** and paste it into Drone. Your presets go in a private gist on your own GitHub account. In a browser where Gas sync is already on, Drone offers a one-tap **Use Gas's Sync**.

## Make your own copy

Click **Use this template** on GitHub, then **Settings → Pages**, source `main`. Everything is in `index.html`, and the sound recipe is in `buildEngine()`.

Made by [M'Gilvry Allen](https://mgilvryallen.com).

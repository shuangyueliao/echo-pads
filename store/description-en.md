# Echo Pads — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Echo Pads is a Simon-style sound memory game: six glowing pads play a
growing pentatonic melody. Watch the sequence, repeat it by ear, and
survive the rising tempo. One wrong pad ends the run.

(203 chars — trimmed below for strict 200-char fields)

Watch six glowing pads play a growing pentatonic melody, then repeat it.
Rounds get longer and faster — one wrong pad ends the run. How far can
your memory go?

## Details

- Genre: Puzzle / Casual / Memory
- Controls: Mouse / Touch (tap the glowing pads). Keyboard: 1–6.
- Modes: Classic (standard tempo, 1-note start) and Speed Round (short
  fast sequences, 3-note start)
- Features: sequence playback speeds up each round (clearly faster past
  round 10), glow-and-ripple feedback, per-mode best scores saved
  locally, mute toggle, single-file HTML5 (no external assets), works
  offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio (pentatonic synthesis:
  C4 D4 E4 G4 A4 C5). No frameworks, no tracking.

## Tags

memory, simon, puzzle, casual, music, brain, arcade, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover 16:9 (1280×720) — to be produced
- [ ] Screenshots — to be produced

## itch.io
- Upload zip (echo-pads-itch.zip), mark "This file is playable in browser",
  entry file: index.html, viewport: square canvas that scales to fit,
  kind: html
- Pricing: $0 (donations optional)

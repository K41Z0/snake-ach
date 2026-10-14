# snake-ach

A tiny Snake game where the food is a **YOLO** achievement badge: every badge you eat makes
the snake longer and the pace faster. Single player, no dependencies, no build step.

Download `index.html` and open it in any browser — the whole game is that one file.

## Play

- **Arrow keys** or **WASD** — move (Russian layout ЦФЫВ works too)
- **Space** or **P** — pause
- **Enter** — start / play again
- On a phone: swipe on the board, or use the on-screen arrows

The best score is kept in `localStorage`, so it survives a reload and stays on your machine.

## Rules

- Eat a badge: +10 points, the snake grows one cell, the tick speeds up a little.
- A wall or your own tail ends the run.
- Every few badges the game hands out an achievement of its own: Quickdraw ⚡, Pull Shark 🦈,
  YOLO 🤠, Starstruck ⭐, Galaxy Brain 🧠.

## Notes

- One file, zero dependencies, works from `file://` — if the browser blocks `localStorage`
  for local files, the game still plays, only the record will not persist.
- Rendered on a `<canvas>` with device-pixel-ratio scaling, so it stays sharp on Retina displays.

## License

MIT — see [LICENSE](LICENSE).

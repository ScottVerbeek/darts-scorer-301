# 🎯 301 Darts Scorer

A progressive web app for scoring 301 darts. Works offline and installs to your home screen.

Hosted staticly via Github Pages: 
 - https://scottverbeek.github.io/darts-scorer-301

## Features

- 1–4 players with custom names
- Single, Double, and Triple multipliers
- Bull (25) and Bull's Eye (50)
- Bust detection (score below 0 or landing on 1)
- Live score preview as you throw
- Undo last dart or last full turn
- Round history log
- Reset or quit back to player setup at any time

## Usage

Tap a modifier (Double / Triple / Bull) first, then tap a number. Hit **Next** to end your turn early, or the turn ends automatically after 3 darts.

## Install as PWA

- **iPhone:** Safari → Share → Add to Home Screen
- **Android:** Chrome → ⋮ → Add to Home Screen

## Files

| File | Description |
|------|-------------|
| `index.html` | App UI and game logic |
| `manifest.json` | PWA metadata (name, theme, icons) |
| `sw.js` | Service worker for offline support |

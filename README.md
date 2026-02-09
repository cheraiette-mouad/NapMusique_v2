# 🎹 Nap Musique v2

An interactive piano learning game built with vanilla HTML, CSS, and JavaScript. Learn to play famous melodies by following falling notes — rhythm-game style!

## 🎮 Features

- **5 difficulty levels** with 5 songs each (25 total)
- **Falling notes system** — hit the right piano key as notes reach the target zone
- **8 piano styles**: Classic, Electric, Synth, Organ, Harpsichord, Music Box, Bell, Marimba
- **Light / Dark theme** with animated backgrounds (aurora, particles, bubbles, spirals, stars…)
- **Score tracking** and progression saved in `localStorage`
- **Web Audio API** synthesis — no audio files needed
- **French note names** (DO, RÉ, MI, FA, SOL, LA, SI)

## 🎵 Song Library

| Level | Songs |
|-------|-------|
| 1 — Débutant | Au Clair de la Lune, Frère Jacques, Twinkle Twinkle, Joyeux Anniversaire, Gamme de Do Majeur |
| 2 — Facile | Ode à la Joie, Lettre à Élise, Mary Had a Little Lamb, London Bridge, Alouette |
| 3 — Intermédiaire | Canon en Ré, Clair de Lune, Gymnopédie No.1, Lac des Cygnes, Menuet en Sol |
| 4 — Avancé | Nocturne Op.9 No.2, Prélude en Do Majeur, Rêverie, Arabesque No.1, Sonate Pathétique |
| 5 — Expert | Fantaisie Impromptu, La Campanella, Valse Minute, Révolutionnaire, Clair de Lune 3ème |

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/cheraiette-mouad/NapMusique_v2.git
   ```
2. Open `index.html` in a browser — no build step or server required.

## 🗂️ Project Structure

```
├── index.html   — Main page layout (home, levels, piano, settings)
├── styles.css   — Styling, animations, themes (4500+ lines)
├── game.js      — Game logic, audio synthesis, state management (2300+ lines)
└── README.md
```

## 🛠️ Tech Stack

- **HTML5 / CSS3** — Glassmorphism UI, CSS animations, custom cursor
- **Vanilla JavaScript** — No frameworks or dependencies
- **Web Audio API** — Real-time piano sound synthesis with multiple waveform styles
- **localStorage** — Progress persistence

## 📄 License

This project is open source.

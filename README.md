# 🏏 Retro Nokia Cricket (1-Bit Monochrome LCD Edition)

<div align="center">

[![HTML5 Canvas](https://img.shields.io/badge/Tech-HTML5%20Canvas%20%2F%20JavaScript-orange?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Monochrome Style](https://img.shields.io/badge/Style-1--Bit%20Nokia%20LCD-8eb828?style=for-the-badge&logo=nokia&logoColor=112306)](https://en.wikipedia.org/wiki/Monochrome_liquid-crystal_display)
[![Web Audio API](https://img.shields.io/badge/Audio-Chiptune%20Piezo%20Buzzer-blue?style=for-the-badge&logo=soundcharts&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Play%20Now-success?style=for-the-badge&logo=google-chrome&logoColor=white)](https://venkatesh-software.github.io/cricket-nokia/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

*A fully playable, nostalgic arcade recreation of the legendary Nokia 1100 monochrome cricket game, built from scratch with retro 1-bit pixel art, perspective pitch mechanics, and procedural 8-bit sound effects.*

[**🎮 Play Live Demo**](https://venkatesh-software.github.io/cricket-nokia/) • [**🕹️ Controls & Gameplay**](#️-how-to-play) • [**🚀 Quick Start**](#-running-locally)

</div>

---

## ✨ Key Features

- **Authentic Nokia 1100 Aesthetics**: Features the iconic olive-green LCD color palette (`#8eb828` background with `#112306` dark pixels), simulated glass glare, scanlines, and high-contrast pixel typography.
- **Pre-Delivery Pitch Preview (`[+]`)**: Anticipate every ball! A blinking crosshair target spot and dotted trajectory line appear before delivery so you can read the pitch and position your batsman.
- **Chill "Easy Pickings" Arcade Pace**: Slower, forgiving ball speeds and generous sweet spots designed for satisfying, clean boundary hits (`4`s and `6`s).
- **Full 10 Wickets & Innings**: Track your runs, overs, run rate, and full 10-wicket lineup just like the classic handheld games.
- **Interactive Crease Movement**: Use the on-screen D-pad or keyboard shortcuts (`4` / `6`) to walk your batsman left and right across the crease with animated stepping and backlift frames.
- **Chiptune Piezo Buzzer Audio**: Powered by the Web Audio API to generate authentic square-wave monophonic audio for button clicks, bat hits, and boundary cheers without external audio files.

---

## 🕹️ How to Play & Controls

| Action | On-Screen Nokia Keypad | Keyboard Shortcut |
| :--- | :--- | :--- |
| **Move Batsman Left** | Tap `◀ STEP L` | `4` or `Left Arrow` |
| **Move Batsman Right** | Tap `STEP R ▶` | `6` or `Right Arrow` |
| **Play Shot / Hit / Bowl** | Tap `5` / Center Button | `5`, `Space`, or Tap Screen |
| **Lofted Shot (Six)** | Tap `2` / Up | `2` or `Up Arrow` |
| **Defensive Block** | Tap `8` / Down | `8` or `Down Arrow` |

---

## 🚀 Running Locally

No bundlers, package managers, or external dependencies are required! This game is built with vanilla HTML5, CSS3, and JavaScript.

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/venkatesh-software/cricket-nokia.git](https://github.com/venkatesh-software/cricket-nokia.git)
   cd cricket-nokia

# 🏎️ Grand Prix

A fast, top-down racing game built with **HTML5, CSS3, and vanilla JavaScript** (Canvas 2D). Dodge incoming traffic, collect nitro cans, and reach the finish line before you run out of lives!

**Play it live:** `https://<your-username>.github.io/<your-repo-name>/`



---

## 🎮 How to Play

| Action | Keyboard | Touch / Mobile |
| --- | --- | --- |
| **Steer** | Arrow keys or `A` / `D` | Left / Right pads (`<` `>`) |
| **Accelerate / Brake** | `W` / `S` | Up / Down pads (`^` `v`) |
| **Nitro Boost** | `Space` | `NITRO` pad |
| **Pause / Resume** | `P` or `Esc` | `II` button |

- **Win Condition:** Reach the distance goal for your chosen difficulty.
- **Lose Condition:** Crash into traffic until all your lives are gone.
- **Scoring System:** Passing a car gives **+10 pts**, collecting a nitro can gives **+25 pts** and **+1 nitro charge** (max 3).

---

## ✨ Features

- **Three Difficulty Levels:** Easy, Normal, and Hard modes adjusting distance goals, top speed, traffic density, and starting lives.
- **Nitro Boost System:** Collect nitro cans on the track and activate hyper-speed bursts with flame animations.
- **High Score Tracking:** Persistent best scores saved locally via browser `localStorage`.
- **Theme Switcher:** Seamless toggle between Dark and Light mode.
- **Pause & Resume:** Take a break anytime during your race.
- **Web Audio API Sound Effects:** Fully synthesized engine hums, crash impacts, and UI sounds without external audio files.
- **Rich Animations:** Countdown timer, screen shake, crash sparks, nitro flames, and an animated progress bar.

---

## 🛠️ Tech Stack

- **HTML5 Canvas** (Game rendering engine)
- **CSS3 Custom Properties** (Styling & Dynamic Themes)
- **JavaScript (ES6+)** (Game logic, physics & state management)
- **Web Audio API** (Procedural sound effects)
- **Git & GitHub Pages** (Version control and automated deployment)

---

## 📂 Project Structure

```text
grand-prix/
├── index.html
├── style.css
│   
├── app.js
│   
└── README.md
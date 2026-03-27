# 🧩 Photo Puzzle

> Turn your photos into beautiful jigsaw puzzles — no account, no server, no limits.

![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## ✨ What is Photo Puzzle?

Photo Puzzle is a browser-based jigsaw puzzle game where users upload their own photos and play them as puzzles. Everything runs locally in the browser — no backend, no uploads, no accounts required.

Built as a portfolio project to demonstrate frontend web development skills including Canvas API, CSS theming, localStorage, and responsive design.

---

## 🚀 Live Demo

👉 **https://bherduran.github.io/photopuzzle/**

---

## 🎮 How It Works

```
Landing Page → Setup → Puzzle Game
```

1. **Upload** 1 to 5 photos from your device
2. **Add captions** to each photo (optional)
3. **Pick a theme** — Romance, Ocean, Nature, Midnight or Minimal
4. **Choose difficulty** — Easy (2×2), Medium (3×3) or Hard (4×4)
5. **Play** — drag and snap pieces into place
6. **Win** — complete all photos to reach the ending screen

---

## 📁 Project Structure

```
Photo Puzzle/
├── index.html      # Landing page
├── setup.html      # Photo upload + customization
├── puzzle.html     # The puzzle game
└── README.md
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 Canvas API | Drawing puzzle pieces and board |
| CSS Custom Properties | Dynamic theme system |
| CSS Grid | Responsive layouts |
| Vanilla JavaScript | Game logic, drag & drop |
| FileReader API | Local photo upload (no server) |
| localStorage | Passing data between pages |
| Intersection Observer | Scroll reveal animations |
| Touch Events | Mobile drag & drop support |
| Bezier Curves | Soft rounded jigsaw shapes |
| Device Pixel Ratio | Retina/HiDPI display support |

---

## 🎨 Themes

| Theme | Colors |
|---|---|
| 💕 Romance | Crimson & Gold |
| 🌊 Ocean | Navy & Cyan |
| 🌿 Nature | Forest & Mint |
| 🌙 Midnight | Deep Purple & Lavender |
| 🖤 Minimal | Black & White |

---

## 🔒 Privacy

**Your photos never leave your device.**

- No server uploads
- No database
- No analytics
- No cookies
- Everything runs 100% in your browser

Photos are read using the `FileReader` API and stored temporarily in `localStorage` for the duration of your session only.

---

## 📱 Device Support

| Device | Support |
|---|---|
| Desktop (Chrome, Firefox, Safari, Edge) | ✅ Full support |
| iPhone / iOS Safari | ✅ Full support |
| Android Chrome | ✅ Full support |
| Tablet | ✅ Full support |


## 🧩 Key Features

- **Real jigsaw shapes** — Soft rounded bezier-curve tabs, not boring squares
- **Smooth snap animation** — Ease-out cubic animation when pieces lock in
- **Anti-overlap scatter** — Pieces spawn around the board without overlapping
- **Per-difficulty board scaling** — Board size auto-adjusts for each difficulty
- **HiDPI support** — Sharp rendering on Retina and high-DPI displays
- **Fully responsive** — Works on any screen size
- **Touch support** — Full drag and snap on mobile

---

## 🗺️ Roadmap

- [ ] Timer mode
- [ ] Piece rotation
- [ ] Share puzzle with a link
- [ ] More difficulty levels
- [ ] Sound effects on snap
- [ ] Puzzle preview mode

---

## 👨‍💻 Author

Built by **Bilge Han Erduran**

- GitHub: [@bherduran](https://github.com/bherduran)




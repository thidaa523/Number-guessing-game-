# 🎯 Guess The Number!

A colorful, single-file number guessing game built with HTML, CSS, and JavaScript — no frameworks, no build step, no external assets.

## 🎮 How to play

1. Open `index.html` in any browser (double-click it — that's it!)
2. Pick a difficulty: Easy (1–50), Normal (1–100), or Hard (1–500)
3. Type a guess and press **Submit** or the **Enter** key
4. Use the ▲ / ▼ chips and the mascot's reactions to zero in on the number
5. Win to trigger confetti and a victory chime — build a win streak!

## ✨ Features

- **Confetti explosion** on every win (HTML5 canvas, custom physics)
- **Sound effects** synthesized live with the Web Audio API (no audio files)
- **Guess history chips** showing ▲ too low / ▼ too high for each attempt
- **Reacting mascot** that changes with how close you are
- **Difficulty levels** with matching accent colors
- **4 color themes**: Candy, Ocean, Sunset, Galaxy
- **Floating emoji background** and a bounce-in card animation
- **Score tracking**: wins, best score, and a fire-growth win streak
- **Everything saves** across page refreshes via `localStorage`

## 🛠️ How it works

The whole game lives in one file:

- **HTML** — the structure (input, buttons, scoreboard, canvas)
- **CSS** — the look (gradients, animations, themes via CSS variables)
- **JavaScript** — the logic (game state, confetti, synthesized sound)

Every line is commented for beginners.

## 🚀 Play online

**https://thidaa523.github.io/Number-guessing-game-/**

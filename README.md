
# 🎯 Number Guessing Duel

A vibrant, fast-paced, and fully mobile-responsive web game where two players face off in a tactical guessing duel. Each player locks in a secret number between 1 and 100, and takes turns trying to crack the opponent's code. First to hit "Bingo!" wins!

Built for ultimate portability, the entire game runs out of a **single HTML file** with zero server overhead.

---

## ✨ Features

- **🎮 Dual Game Modes:**
  - **Pass & Play (Local):** Play with a friend on a single device. The UI intelligently hides secret inputs to prevent peeking between turns.
  - **Online P2P Duel (Remote):** Challenge a friend on a different phone! Generates an instant invite link utilizing **PeerJS** for a serverless, real-time connection directly between browsers.
- **📱 Mobile-First Design:** Fully optimized for all smartphone screens with touch-friendly controls, adaptive layouts, and smooth transitions.
- **🎨 Fun & Vibrant UI:** Styled with modern, high-energy Tailwind CSS gradients that look great in both casual and competitive sessions.
- **📊 Real-Time Scoreboard:** Keeps track of active turns, total wins, and a detailed match history for both players.

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript** (ES6+)
- **Tailwind CSS** (via CDN) for modern, utility-first styling
- **PeerJS** (via CDN) for serverless WebRTC data connections

---

## 🚀 How to Play

1. **Clone the repository** or simply download the `index.html` file.
2. **Open the file** in any modern mobile or desktop browser.
3. Choose your mode:
   - **Local:** Pass the phone back and forth.
   - **Online:** Copy the generated room link, send it to a friend, and start guessing as soon as they connect!

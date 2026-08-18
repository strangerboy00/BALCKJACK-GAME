# 🃏 Blackjack Web Game

A classic Blackjack (21) browser game built with vanilla **HTML5**, **CSS3**, and **JavaScript**[cite: 1, 2, 3]. Test your luck, draw cards, and see if you can hit 21 without going bust!

---

## 🚀 Live Demo

🔗 **[Live Deployment Link](https://strangerboy00.github.io/BALCKJACK-GAME/)**  
*(Replace this placeholder URL with your live link on GitHub Pages, Netlify, or Vercel)*

---

## 📌 Features

- **Dynamic Card Dealing:** Generates random cards with realistic values (Ace = 11, Face cards = 10, Number cards = 2–10)[cite: 1].
- **Game State Tracking:** Real-time calculation of your card sum and instant feedback[cite: 1]:
  - 🟢 **Sum < 21:** Prompted to draw another card[cite: 1].
  - 🏆 **Sum = 21:** Blackjack! You win[cite: 1]!
  - 🔴 **Sum > 21:** Bust! You're out of the game[cite: 1].
- **Player Stats:** Displays player name and chip balance[cite: 1].
- **Clean Casino-Style UI:** Stylized casino table background and button controls[cite: 2, 3].

---

## 🎮 How to Play

1. Click **START GAME** to deal your initial two cards[cite: 1, 2].
2. Review your card sum[cite: 1]:
   - If your total is **under 21**, click **NEW CARD** to draw another card[cite: 1, 2].
   - If your total hits **21**, you score **Blackjack**[cite: 1]!
   - If your total exceeds **21**, you are out of the game[cite: 1].
3. Click **START GAME** again to reset and start a fresh round[cite: 1, 2].

---

## 📂 Project Structure

```text
├── index.html        # Main HTML structure and UI elements
├── index.css         # Styling and casino theme layout
├── index.js          # Core game logic and state management[cite: 1]
├── images/           # Assets (e.g., table background)[cite: 3]
└── README.md         # Project documentation

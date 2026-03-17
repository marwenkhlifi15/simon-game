# Simon Game 🎮

A simple classic **Simon Game** built with **HTML, CSS, and JavaScript**.  
The goal is to remember and repeat an increasingly long sequence of colors.

🔗 **Live Demo**: https://marwenkhlifi15.github.io/simon-game/

---

## 🎯 Project Goals

- Practice **DOM manipulation** with JavaScript.
- Work with **keyboard and click events**.
- Use **arrays**, **random sequences**, and basic game logic.
- Add simple **sounds and animations** to improve the user experience.

---

## 🧩 How to Play

1. Press **any key** on your keyboard to start the game.
2. The game will show a sequence of colors (starting with one, then increasing).
3. Click on the color buttons in **the same order** as the sequence.
4. If you click the wrong color:
   - A “wrong” sound is played.
   - The screen flashes red.
   - The message “*Game Over, Press Any Key to Restart*” is shown.
5. Press any key again to **restart from level 1**.

---

## 🛠️ Tech Stack

- **HTML5** – page structure  
- **CSS3** – styling and layout  
- **JavaScript (ES6)** – game logic  
- **jQuery** – simpler DOM selection and event handling  
- **Audio** – sounds for each button + error sound  

---

## 📂 Project Structure

```text
.
├── index.html    # Main page
├── styles.css    # Styles (layout, colors, animations)
├── game.js       # Game logic (sequence, user input, checks)
└── sounds/       # Audio files
    ├── red.mp3
    ├── blue.mp3
    ├── green.mp3
    ├── yellow.mp3
    └── wrong.mp3

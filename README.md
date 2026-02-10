# 🎣 Fishing Game — HTML5 Phaser 3

Casual fishing mini-game built with Phaser 3.
Player controls a fishing hook from a boat to catch fish, manage timing, and reach the target score before running out of lives or time.

---



## 🚀 Live Demo

*( GitHub Pages)*
(https://michaelpransiscop.github.io/proyek-fishing-game/)

---

## 🎮 Gameplay Features

* 🎣 Manual fishing mechanic (skill-based timing)
* 🚤 Boat position control (left/right movement)
* 🐟 Multiple fish sizes:

  * Small fish = 1 point
  * Big fish = 3 points
* 🎯 Target score system
* ❤️ Lives system (missed catches reduce lives)
* ⏱ Countdown timer
* ⏸ Pause / Resume feature
* 🔁 Restart on win/lose
* 🧵 Visual fishing line animation
* 🖱 Click-based hook control:

  * Click 1x → Drop hook
  * Click 2x → Stop in water
  * Click 3x → Pull up

---

## 🕹 Controls

| Action             | Input          |
| ------------------ | -------------- |
| Move hook          |Mouse click      |
| Drop fishing line  | Mouse click    |
| Stop hook in water | Mouse click    |
| Pull hook up       | Mouse click    |
| Pause/Resume       | Pause button   |

---

## 🧠 Game Mechanics

* Player must catch fish efficiently before:

  * Time runs out, or
  * Lives reach zero
* Pulling the hook without catching a fish:

  * ❤️ −1 life
* Winning condition:

  * Reach target score
* Losing condition:

  * No lives left
  * Timer reaches 0

---

## 🛠 Tech Stack

* HTML5
* JavaScript (Vanilla)
* Phaser 3 — 2D Game Framework
* Arcade Physics System

---

## 📂 Project Structure

```
proyek-fishing-game/
│
├── index.html        # Main game file
├── README.md
```

---

## ▶️ How to Run Locally

```bash
git clone https://github.com/MichaelPransiscoP/proyek-fishing-game.git
cd proyek-fishing-game
```

Open:

```
index.html
```

Run directly in browser:

* Chrome
* Edge
* Firefox

---

## 🌱 Future Improvements

* 🦈 Enemy sharks (obstacle mechanic)
* 💰 Currency & upgrade system
* 🎣 Equipment progression
* 🔊 Sound effects & background music
* 📱 Mobile touch controls
* 🏆 High score saving
* 🌊 Animated water background
* 🎮 Multi-level difficulty scaling

---

## 💼 Portfolio Notes

This project demonstrates:

* Game logic implementation
* State management (Menu, Playing, Pause, Game Over)
* Physics interaction using Phaser
* UI system with dynamic text updates
* Timing & scoring mechanics
* Input handling (mouse + keyboard)

---

## 👨‍💻 Author

**Michael Pransisco**

GitHub:
[https://github.com/MichaelPransiscoP](https://github.com/MichaelPransiscoP)

---

## 📜 License

Free to use for learning & portfolio purposes.

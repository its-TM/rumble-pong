# 🕹️ Rumble Pong

**Rumble Pong** is a powerup-enhanced retro-style Pong game built with HTML5, CSS, and JavaScript using the p5.js library. The game features classic two-player pong gameplay with an exciting twist—powerups that can freeze the ball, shrink paddles, and more!

## 🎮 Features

- 🎮 Classic two-player pong gameplay
- ⚡ Powerups like Freeze, Fireball, and more (Play to Find 'em all)
- 🔊 Retro-styled sound and music
- 🕹 Stylish main menu with volume toggle
- 🖥 Responsive canvas scaling for various screen sizes

## 🗂 Project Structure
rumble-pong/
├── Main Menu.html # Main menu page with navigation and sound toggle
├── pong.html # Main game implementation using p5.js
├── LICENSE
├── Data
    ├── music.mp3 # Background music
    ├── volumeoff.png # Volume icon (off)
    ├── volumeon.png # Volume icon (on)
    ├── retro.mp4
    └── ding.mp4

## 🚀 Getting Started

### 📦 Prerequisites

No setup required! Just make sure you have a browser that supports HTML5 and JavaScript.

### ▶️ To Run

1. Clone or download the repository.
2. Open `Main Menu.html` in your browser.
3. Click **Play Game** to start.

> 💡 Make sure all image/audio assets are placed in the same directory for proper loading.

## 🕹 Controls (Can be changed from settings page)

| Player | Action       | Key       |
|--------|--------------|-----------|
| P1     | Move Up      | `W`       |
| P1     | Move Down    | `S`       |
| P1     | Use Powerup  | `Q`       |
| P2     | Move Up      | `I`       |
| P2     | Move Down    | `K`       |
| P2     | Use Powerup  | `P`       |

## 🧠 Powerups

Powerups appear every 8 seconds and include:
- ❄️ **Freeze**: Freezes the ball temporarily.
- 🔥 **Fireball**: Doubles the ball’s speed.
- 📏 **XL**: Increases your paddle size.
- 🔽 **Mini**: Shrinks opponent’s paddle.
- 🧹 **Magic**: Changes trajectory and speed of the ball. 
- ⌨️ **Broken Keyboard**: Inverts the opponent's controls.
- 🧲 **Force Field**: Creates a shield in front of your paddle.

## 🛠 Built With

- [p5.js](https://p5js.org/) - JavaScript library for creative coding
- HTML5 + CSS3 - UI and layout

## 📄 License

This project is open source under the [MIT License](LICENSE).

## 🙌 Acknowledgments

- Inspired by classic Pong and Rocket League. 
- Fonts and icons by [Google Fonts](https://fonts.google.com/specimen/Press+Start+2P) and free icon resources.

---

Enjoy playing **Rumble Pong** and unleash the chaos! 🚀

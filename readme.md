# 🚀 Space Shooter

> **Built entirely by voice.** Every line of this game started as something I said out loud, using [Wispr Flow](https://ref.wisprflow.ai/hhg).

A browser space shooter built with a single HTML file, an HTML canvas, and plain JavaScript. No libraries.

🎬 **Demo video:** _add link here_  
🕹️ **Play it live:** _add link here_

---

## 🎙️ Built with my voice

This project wasn't typed, it was spoken. I talked to Wispr Flow, and my words became prompts that turned into a working game. I started with a simple ship and kept evolving it one sentence at a time:

> "Make enemies move faster as the score increases."
>
> "Add a boss every 30 seconds with a health bar."
>
> "Add screen shake when the player loses a life or the boss is defeated."

When something broke, I described the bug out loud and fixed it the same way. The full build, from the first prompt to the final game, is shown in the demo video.

---

## 🎮 How to play

Open `index.html` in your browser. Move along the bottom of the screen, shoot enemies as they fall, collect power-ups, and take down the boss. You have three lives. The game ends when they run out.

### Controls

| Key | Action |
| --- | --- |
| **Left Arrow** | Move left |
| **Right Arrow** | Move right |
| **Space** | Shoot |
| **Enter** | Restart after game over |

---

## ✨ Features

- Player ship that moves left and right and fires upward
- Enemies that spawn at random positions and fall from the top
- Score that increases by 10 for each enemy destroyed
- Enemies that get faster every 100 points
- Three lives, with a brief invincible blink after taking a hit
- Game over when the last life is lost
- Occasional glowing green power-up that grants triple shot for 10 seconds
- Colorful particle explosions when enemies are destroyed
- A larger boss every 30 seconds with a health bar; it takes 10 hits and drifts sideways while slowly dropping in
- Screen shake when you lose a life or defeat the boss
- High score saved in local storage and shown on screen
- Parallax star field with stars scrolling at different speeds

---

## 🛠️ Tech

- HTML5 canvas
- Plain JavaScript, in a single `index.html` file
- No libraries, no build step, no dependencies

---

## 🗣️ Made with Wispr Flow

This entire project was built using voice with Wispr Flow.

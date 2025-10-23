# The Drive - A JavaScript Pseudo-3D Racer

<p align="center">
  <img src="Img/the-drive.gif" alt="Gameplay GIF of The Drive" width="800"/>
</p>

<h3 align="center">
  <a href="https://shreys1611.github.io/The-Drive/">
    ► Click Here to Play the Game Live! ◄
  </a>
</h3>

## A Technical Re-implementation of a Classic

**The Drive** is a fast-paced, pixel-art endless runner built from scratch using only HTML, CSS, and JavaScript. This project was a solo endeavor to re-implement and build upon the core mechanics of a classic 1980s "pseudo-3D" arcade racer.

My goal was to use this as a technical challenge to build a complete game loop from the ground up, focusing on the JavaScript logic required to create a fast, dynamic, and fun web-based game.

---

### Disclaimer: Inspiration & Credits

This project was heavily inspired by a popular open-source JavaScript racing game, which itself is a brilliant tribute to the 1986 arcade classic *Out Run*.

The pixel art sprites for the car, obstacles, and environment are **identical to and sourced from that open-source project.** I did not create the art. My focus was purely on the engineering challenge of writing my own JavaScript implementation of the game's core systems, such as the high-score logic, collision penalties, and procedural track generation.

---

### ✨ Key Features (My Implementation)

* **High Score System:** Tracks the player's current score and saves their all-time high score using the browser's `localStorage`.
* **Collision Penalty:** Crashing into obstacles doesn't end the run, but it punishes the player by significantly reducing their speed, adding a layer of strategy.
* **Dynamic Environment:** The road is not a straight line! I wrote the logic to procedurally generate the road's hills, turns, and obstacle placements to ensure every run feels unique.

---

### 💻 Technical Implementation

This project was a deep dive into JavaScript-based game development. The entire game logic is contained in a single `script.js` file:

* **Game Loop:** A core `update()` function that runs on every frame to handle logic.
* **Player Controls:** Listens for keyboard input to move the car left and right.
* **Procedural Generation:** Wrote all the logic that dynamically generates the road's curves, hills, and obstacle patterns.
* **Collision Detection:** Functions that check for overlap between the player's car and any obstacles on the road.
* **Score & State Management:** Wrote all the logic for managing the game's state and for saving/loading the high score.

---

### 🔧 Tech Stack

* **Frontend:** HTML5
* **Styling:** CSS3
* **Core Logic:** JavaScript (ES6+)

---

### 🚀 How to Play

This game is designed to be played directly in your browser!

1.  **Click the link at the top of this page:** [https://Shreys1611.github.io/The-Drive/](https://Shreys1611.github.io/The-Drive/)
2.  Use the `A` and `D` keys (or Arrow Keys) to steer your car.
3.  Dodge the obstacles and aim for the high score!

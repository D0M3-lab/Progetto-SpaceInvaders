# 👾 Space Invaders

**Classic Space Invaders Game in Python with Tkinter**

This program is a Python-based implementation of the classic **Space Invaders** game, built using the **Tkinter** library for the graphical interface.  
It features a player-controlled spaceship, destructible barriers, enemy invaders, sprite-based graphics, and full collision detection.

---

## 🎮 Key Features & Functionality

---

### 🚀 1. Player Controls & Movement

- Control the spaceship using **left** and **right arrow keys** to move horizontally.
- Press the **spacebar** to shoot bullets from the center of the spaceship.

---

### 👾 2. Enemies

- A grid of enemies moves **horizontally** across the screen.
- When hitting a screen edge, they **drop down** and **reverse direction**.
- Enemies **randomly fire bullets** toward the player.

---

### 🛡️ 3. Barriers

- **Destructible barriers** are placed near the bottom of the screen.
- The player can hide behind barriers for protection.
- Barriers are **gradually destroyed** by both:
  - **Enemy bullets**
  - **Player bullets**

---

### 💥 4. Collision Detection

- The game checks for:
  - Player bullet ↔ Enemy
  - Enemy bullet ↔ Player
  - Any bullet ↔ Barrier

- **On hit**:
  - Enemies are destroyed → **+10 points**
  - Barrier segments are damaged
  - Player is hit → **Game Over**

---

### 🧮 5. Scoring

- **+10 points** per enemy destroyed
- The **score is displayed** at the top and updates in real-time

---

### ❌ 6. Game Over & Win Condition

- **Game Over** triggers if:
  - An enemy reaches the bottom
  - The player is hit by an enemy bullet

- **You Win!** message is shown if:
  - All enemies are destroyed

- A **"Restart"** button allows the player to reset the game after the end.

---

### 🔁 7. Restart Functionality

- After Game Over or Win:
  - Click **"Restart"** to reset:
    - Enemies
    - Score
    - Game state

---

### ⚙️ 8. Game Mechanics

- A **fire delay** prevents the player from shooting continuously.
- **Enemy bullets** are fired **randomly** during each game update cycle.

---

### 🖼️ 9. Visual Elements

- The game uses **sprites** for:
  - Player spaceship
  - Enemies
  - Bullets

- Images are loaded from external files (e.g.:
  - `'player.png'`
  - `'enemy.png'`
  - `'bullet.png'`)

- Sprites are **resized** to fit the game dimensions appropriately.

---

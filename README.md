# 🏓 Pong Game in Python (Turtle Graphics)

A classic Pong arcade game built using Python and the Turtle graphics module. Two players can control paddles using keyboard inputs to bounce the ball back and forth. The game includes dynamic ball movement, scoring, paddle collisions, and a scoreboard.

---

## 📸 Demo Screenshot


![image](https://github.com/user-attachments/assets/9640ec89-44a2-44ac-9929-52c22f86a2d5)




---

## 🧠 Game Features

- **Two-Player Paddle Control**
  - Player 1 (Left): `W` and `S` keys to move up/down.
  - Player 2 (Right): `Up` and `Down` arrow keys.
- **Bouncing Ball**
  - The ball bounces off the top and bottom walls.
  - The ball also bounces back if it hits a paddle.
- **Scoring System**
  - If a player misses the ball, the opponent scores a point.
  - Scoreboard displays live score updates.

---

## 📁 Project Structure

```bash
pong-game/
│
├── main.py           # Main game loop and setup
├── paddle.py         # Paddle class for movement
├── ball.py           # Ball class for movement and collision
├── scoreboard.py     # Scoreboard class for tracking and displaying scores
├── README.md         # Project description and documentation
└── screenshot.png    # Screenshot of the game (optional)


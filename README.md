# Real-Time Ping Pong Game 🏓

A classic arcade-style Ping Pong game built with Python and Pygame. This project features a player-controlled paddle competing against a responsive AI opponent in a fast-paced, real-time match.



## Features

* **Player vs. AI Gameplay:** Control your paddle with the `W` and `S` keys and challenge the built-in AI.
* **Dynamic Ball Physics:** The ball's bounce angle changes depending on where it hits the paddle, allowing for more strategic gameplay.
* **Robust Collision Detection:** Enhanced collision logic prevents the ball from passing through paddles, even at high speeds.
* **Game Over & Replay:** The game detects when a player has won and displays a game-over screen.
* **Replay Menu:** After a match, you can choose to play again in a "Best of 3," "Best of 5," or "Best of 7" format, or exit the game.
* **Sound Effects:** Audio feedback for paddle hits, wall bounces, and scoring points makes the game more immersive.

---

## Technologies Used

* **Python 3**
* **Pygame**

---

## Getting Started

Follow these instructions to get the project running on your local machine.

### **Prerequisites**

* Python 3.10 or newer installed on your system.

### **Setup & Installation**

1.  Clone the repository to your local machine:
    ```bash
    git clone <your-repository-url>
    ```

2.  Navigate to the project directory:
    ```bash
    cd pygame-pingpong
    ```

3.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4.  Run the game:
    ```bash
    python main.py
    ```

---

## How to Play

* **Player Controls:**
    * `W` key: Move your paddle up.
    * `S` key: Move your paddle down.
* **Objective:** Be the first to score the required number of points to win the match. A point is scored when the ball gets past your opponent's paddle.
* **Replay Menu:** After a game ends, press `3`, `5`, or `7` to start a new match, or press `ESC` to quit.

---


## Folder Structure

```
pygame-pingpong/
├── main.py
├── requirements.txt
├── game/
│   ├── game_engine.py
│   ├── paddle.py
│   └── ball.py
├── assets/
│   ├── paddle_hit.wav
│   ├── score.wav
│   └── wall_bounce.wav
└── README.md
```

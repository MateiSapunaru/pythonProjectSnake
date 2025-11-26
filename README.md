````markdown
# Matei's First Python Game 🎮

Simple Snake clone written in Python with Pygame.  
Nothing fancy, just me playing around and learning how game loops, input, and basic rendering work.

---

## Requirements

- Python 3.x
- `pygame` library

Install Pygame with:

```bash
pip install pygame
````

---

## How to run

From the project folder:

```bash
python main.py
```

(or whatever you named the file that contains the code)

A window should pop up with the game running at 720x480.

---

## How to play

* Use the **arrow keys** to move the snake:

  * ↑ up
  * ↓ down
  * ← left
  * → right

* Eat the **white square** (fruit) to grow and increase your score.

* If you hit the wall or your own body, the game is over.

When the game ends:

* Press **Y** to play again
* Press **N** to quit

Your current score is always shown in the top-left corner.

---

## Tweaks you can make

If you want to play with it a bit:

* Change the snake speed:

  ```python
  snake_speed = 15
  ```

* Change the window size:

  ```python
  window_x = 720
  window_y = 480
  ```

* Edit colors or sizes to make it look different.

---

This is mostly a learning project for me, but if you stumble on it and improve it, feel free to build on top of it.

```

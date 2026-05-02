#  Memory Grid Game

An interactive memory-based puzzle game built with Python and Tkinter.  
Test your memory by remembering the position of numbers on a grid — 
then click them in the correct order before time runs out!

---

##  How to Play

1. A grid of numbers appears — **memorize their positions**
2. After a few seconds the numbers **hide behind "?"**
3. Click the buttons in **ascending order (1, 2, 3...)** before time runs out
4. Complete Level 1 to unlock Level 2 with a bigger grid!

---

##  Levels

| Level | Grid Size | Memorize Time | Play Time |
|-------|-----------|---------------|-----------|
| 1     | 3 × 3     | 3 seconds     | 20 seconds|
| 2     | 4 × 4     | 7 seconds     | 30 seconds|

---

##  Tech Stack

- **Python** — core programming language
- **Tkinter** — GUI library for the game interface
- **random** — for shuffling number positions every round
- **messagebox** — for win/loss pop-up alerts
- **lambda functions** — for dynamic button event binding

---

##  How to Run

Make sure Python is installed, then run:

```bash
python memory_game.py
```

No additional libraries needed — uses Python's built-in modules only.

---

##  Concepts Used

- GUI development with Tkinter
- Dynamic widget creation and grid layout
- Event-driven programming with button callbacks
- Game state management using global variables
- Countdown timer using `root.after()` (non-blocking)
- Lambda functions for passing arguments to button commands

---

##  Future Improvements

- Add more levels with larger grids
- Add a scoring system based on time remaining
- Add sound effects on correct/wrong clicks
- Save high scores locally

---

## 👩‍💻 Author

Shravee Shah | IT Student at MKSSS's Cummins College of Engineering for Women  

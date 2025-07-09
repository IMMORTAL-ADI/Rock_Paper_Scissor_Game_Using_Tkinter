# Rock Paper Scissor Game Using Tkinter

This is a simple Rock-Paper-Scissor game built with Python's Tkinter library for the GUI. The game allows you to play against the computer, with scores tracked and images displayed for each move.

## Features
- Play Rock, Paper, or Scissors against the computer
- Visual feedback with hand images for both player and computer
- Score tracking for both player and computer
- Simple and interactive GUI

## Requirements
- Python 3.x
- Tkinter (usually included with Python)
- Pillow (for image handling)

Install Pillow if you don't have it:
```bash
pip install pillow
```

## Setup
1. Clone or download this repository.
2. Ensure the `Hand_Images` folder is in the same directory as `Rps_game.py` and contains:
   - `rock1.jpeg`, `rock2.jpeg`
   - `paper1.png`, `paper2.png`
   - `scissor1.png`, `scissor2.png`
3. Make sure the image file paths in `Rps_game.py` are set to the correct relative paths:
   ```python
   self.rock_1 = ImageTk.PhotoImage(file="Hand_Images/rock1.jpeg")
   self.paper_1 = ImageTk.PhotoImage(file="Hand_Images/paper1.png")
   self.scissor_1 = ImageTk.PhotoImage(file="Hand_Images/scissor1.png")
   self.rock_2 = ImageTk.PhotoImage(file="Hand_Images/rock2.jpeg")
   self.paper_2 = ImageTk.PhotoImage(file="Hand_Images/paper2.png")
   self.scissor_2 = ImageTk.PhotoImage(file="Hand_Images/scissor2.png")
   ```
   (Update the code if needed to use these relative paths.)

## How to Run
Run the following command in your terminal:
```bash
python Rps_game.py
```

## Gameplay
- Click on ROCK, PAPER, or SCISSOR to make your move.
- The computer will randomly select its move.
- The winner of each round is displayed, and scores are updated.
- Click QUIT to exit the game.

---
Enjoy playing!


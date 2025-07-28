# Car-Game

A simple yet exciting car racing game built in Python using the [pygame](https://pygame.org/) library. Dodge incoming cars, rack up your score, and see how long you can survive. Designed and developed by [Utkarsh Mathur](mailto:utkarshbmathur04@gmail.com).

---

## Author

- **Utkarsh Mathur**
- 📧 utkarsbmathur04@gmail.com
- 📆 27-July-2025

---

## Features

- **Real-time car movement** with keyboard controls (Left/Right arrow keys)
- **Enemy car** that appears randomly and speeds up over time
- **Scrolling background** for immersive gameplay
- **Score tracking** during gameplay
- **Game Over dialog** and restart option
- **Credit display** screen

## Requirements

- Python 3.7 or newer
- [pygame](https://pygame.org/) (install with `pip install pygame`)
- Game images (`img/car.png`, `img/enemy_car_1.png`, `img/back_ground.jpg` in an `img/` folder next to your script)

## How to Run

1. **Install Python** (if you haven’t already):  
   [Download Python here](https://www.python.org/downloads/)

2. **Install pygame:**
- pip install pygame


3. **Clone or download the repository**, and make sure all image assets are present in an `img/` directory:
 - `img/car.png`: Player's car image
 - `img/enemy_car_1.png`: Enemy car image
 - `img/back_ground.jpg`: Background road image

4. **Run the game:**
- python scriptname.py

Replace `<scriptname>.py` with your Python file name (e.g. `car_game.py`).

## Controls

- **Left Arrow**: Move car to the left
- **Right Arrow**: Move car to the right

## Gameplay Technical Details

- The player car moves in discrete steps left/right and cannot cross road boundaries (crashing ends the game).
- An enemy car falls down from a random x-position; speed increases as your score gets higher.
- Scrolling background simulates road movement.
- Collision detection checks if the player's car overlaps with the enemy car or touches the road boundary.
- Score increases automatically with time survived.

## Acknowledgements

- Original gameplay inspiration and some sprites credited to Anuj Kumar (`cdac.anuj@gmail.com`) as referenced in the code.
- Built using the [pygame](https://pygame.org/) game development framework.

---

**Enjoy Racing! 🚗**

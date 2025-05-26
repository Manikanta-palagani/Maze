# 3D Maze Coin Collector Game (Ursina Engine)

🎮 Game Overview

This is a 3D first-person coin collection game built using the [Ursina Game Engine](https://www.ursinaengine.org/). The player navigates a maze-like environment, collects coins to increase score, and maintains health that gradually depletes over time. The player can also save and load their progress.

# Features:
- First-person character controller
- Maze environment (`maze.obj`)
- Coin collection with interactive UI prompt
- Score display and health bar UI
- Save (`F5`) and Load (`F9`) system using JSON

---

## 🛠️ Installation Steps

1. **Install Python 3.8 or higher**  
   [Download Python](https://www.python.org/downloads/)

2. **Install Ursina Engine**
   ```bash
   pip install ursina

   Download or clone the repository

bash
Copy
Edit
git clone https://github.com/Manikanta-palagani/Maze.git
cd ursina-coin-maze-game
Place the maze.obj model in the project directory.

This file must be named exactly maze.obj and should represent the 3D maze environment.

Run the game

bash
Copy
Edit
python main.py


# Controls
Key	Action
W/A/S/D	Move forward/left/back/right
Space	Jump
Mouse	Look around (FPS controls)
E	Collect nearby coins
F5	Save game
F9	Load saved game

📜 Credits and License
👨‍💻 Developed By:
Manikanta

🧱 Built With:
Ursina Engine

Python 3

🪙 Assets:
Coins: Procedural gold-colored spheres

Maze: Custom or downloaded maze.obj file

UI: Ursina text and quad elements

📄 License:
This project is licensed under the MIT License.
You are free to use, modify, and distribute it with attribution.



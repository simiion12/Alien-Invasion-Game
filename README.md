# Alien-Invasion-Game

Welcome to **Alien Invasion**, a classic arcade-style game where you defend the Earth from waves of alien attacks! This project is part of the exercises from *Python Crash Course, 2nd Edition* by Eric Matthes, built using Python and Pygame.

## Game Overview

In **Alien Invasion**, you control a spaceship that moves horizontally at the bottom of the screen. Your goal is to shoot and destroy waves of aliens before they reach you or the bottom of the screen. The game increases in difficulty as you progress through each wave.

## Features

- Player-controlled spaceship with smooth movement.
- Aliens that appear in progressively harder waves.
- Ability to shoot bullets to destroy incoming enemies.
- Score tracking for each alien defeated.
- Game ends when aliens reach the bottom or collide with your ship.

## Controls

- **Move left**: `←` (Left Arrow)
- **Move right**: `→` (Right Arrow)
- **Shoot**: `Spacebar`

## Setup Instructions

To run the game locally, follow these steps:

### 1. Install Python and Pygame
Make sure you have Python installed. Then install Pygame by running:

```bash
pip install pygame
```

### 2. Clone the Repository
Clone the project repository from GitHub:
```bash
git clone https://github.com/yourusername/alien-invasion.git
cd Alien Invasion
```

### 3. Run the Game
Once everything is set up, run the following command to start the game:
```bash
python alien_invasion.py
```

### 3. Folder Structure
```bash
Alien-Invasion-Game/
│
├── alien_invasion.py      # Main game file
├── settings.py            # Game settings (screen, speed, etc.)
├── ship.py                # Player spaceship class
├── alien.py               # Alien class
├── bullet.py              # Bullet class
├── game_functions.py      # Core game mechanics
├── scoreoard.py           # Scoreboard class
├── game_stats.py          # CGame stats class
└── images                 # Images folder
```

### 4. Future Enhancements
Some potential improvements for the game include:

- Adding power-ups like rapid fire or shields.
- Implementing different alien types and behaviors.
- Introducing high-score saving for future games.
- Adding sound effects and background music.

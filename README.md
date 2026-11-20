#  Lunar Lander – Lab 4

## Project Overview

Lunar Lander is a Python-based game developed using Pygame. The player controls a spacecraft and attempts to land safely on the lunar surface while managing fuel, speed, and landing angle.

This lab focuses on debugging, physics-based game logic, landing validation, and implementing additional gameplay features using AI-assisted development.

## Technologies Used

- Python 3
- Pygame

## Tasks Completed

### Task 1 – Touchdown Validation
Fixed the touchdown validation bug by checking the spacecraft's horizontal speed (`MAX_SPEED_X`), vertical speed (`MAX_SPEED_Y`), and landing angle (`MAX_ANGLE`). The spacecraft must satisfy all landing conditions to achieve a safe landing.

### Task 2 – Ship Color Based on Fuel
Implemented `ship_color(fuel_ratio)` to dynamically change the spacecraft's color based on the remaining fuel. The ship's color shifts toward red as fuel decreases.

### Task 3 – Landing Effect
Implemented `on_landing(score)` to trigger a fireworks particle effect when the spacecraft lands successfully.

### Task 4 – Bonus Life
Implemented `bonus_life_threshold()` with a score threshold of 1500. Bonus lives are awarded automatically when the player reaches the required score milestones.

## Game Features

- Spacecraft rotation and thrust
- Gravity and physics-based movement
- Fuel management
- Horizontal screen wrapping
- Procedurally generated terrain
- Two landing pads with different score multipliers
- Landing validation based on speed and angle
- Score, level, and lives tracking
- Fireworks landing effect
- Bonus lives based on score

## Controls

| Key | Action |
|---|---|
| Left Arrow | Rotate left |
| Right Arrow | Rotate right |
| Up Arrow | Apply thrust |
| R | Reset game |
| Space | Continue after landing or crashing |

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/poojithareddyrk-jpg/32_lunarLander.git
   ```

2. Navigate to the project directory:

   ```bash
   cd 32_lunarLander
   ```

3. Install Pygame:

   ```bash
   pip install pygame
   ```

4. Run the game:

   ```bash
   python game.py
   ```

## Submission Evidence

### Before Modification – Gameplay Video
The video demonstrates the original touchdown validation bug before the fix.

### After Modification – Gameplay Video
The video demonstrates the corrected touchdown validation and the implemented gameplay features.

**Google Drive – Lab 4 Videos and Submission Evidence:**
[Open Drive Folder](https://drive.google.com/drive/folders/12lvGPXnbArDxkLwwgIR-29G5V8VN1jtr?usp=drive_link)

## Author

**Poojitha P**
PES University – Lab 4

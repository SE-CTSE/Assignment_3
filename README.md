## 3D Dinosaur Game with Unity

<img width="758" alt="image" src="https://github.com/SE-CTSE/Assignment_3/assets/67488752/624466d2-cafc-430c-8008-f2b4da852984">



## Overview

This Unity project implements a 3D dinosaur game where players control a dinosaur character, avoid obstacles, and collect points. The game features dynamic movement mechanics, an increasing difficulty level, and a responsive user interface.

## How to Play

- **Controls:** Use the arrow keys to move the dinosaur forward, backward, left, and right. Press the spacebar to make the dinosaur jump over obstacles.
- **Objective:** Navigate the dinosaur through the environment, avoiding obstacles and collecting points.
- **Scoring:** Points are awarded for every obstacle successfully avoided. The game ends when the dinosaur collides with an obstacle.
- **Restart:** If the game ends, press the 'R' key to restart and try again.

## Components

### DinosaurController

- **Description:** Controls the movement and jumping behavior of the dinosaur character.

- **Features:**
  - Forward movement at a constant speed.
  - Ability to jump using the spacebar.
  - Detection of ground collision for proper jumping mechanics.

### GameController

- **Description:** Manages the game's score system and controls the game over state.
- **Features:**
  - Text display of the current score.
  - Detection of game over conditions.
  - Option to restart the game after game over.

### ObstacleSpawner

- **Description:** Spawns obstacles at regular intervals to challenge the player.
- **Features:**
  - Instantiation of obstacles ahead of the player's position.
  - Randomized spawn positions within a defined range.

## Installation

To run the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in Unity.
3. Ensure that you have the necessary Unity version installed (mention the version here).
4. Run the game in the Unity Editor or build it for your desired platform.
5. you can directly use our apk file also.

# Pac-Man (Java Swing)

A classic Pac-Man clone built in Java using `javax.swing` and `java.awt`, featuring a custom tile-based map, ghost AI, sound effects, level progression, power pellets, and tunnel wrap-around.

## Features

- **Classic gameplay** — navigate Pac-Man through a maze, eat food dots, avoid ghosts
- **Sound effects** — plays audio on eating food, dying, and game over
- **Level progression** — clearing all food advances the level and speeds up the game
- **Power pellets** — four large pellets in the map corners; eating one lets Pac-Man eat ghosts for bonus points (+200) for a limited time
- **Tunnel wrap-around** — Pac-Man exits one side of the map and reappears on the opposite side through the ghost-spawn row
- **Pause** — press `P` to pause/unpause mid-game
- **Lives and scoring** — 3 lives, score tracked and displayed on screen

## Controls

| Key | Action |
|---|---|
| Arrow Up | Move up |
| Arrow Down | Move down |
| Arrow Left | Move left |
| Arrow Right | Move right |
| P | Pause / unpause |
| Any key | Restart after Game Over |

## Requirements

- Java JDK 8 or higher
- The following image assets in the same folder as `PacMan.java`:
  - `wall.png`
  - `blueGhost.png`, `orangeGhost.png`, `pinkGhost.png`, `redGhost.png`
  - `pacmanUp.png`, `pacmanDown.png`, `pacmanLeft.png`, `pacmanRight.png`
- The following sound assets (`.wav` format) in the same folder:
  - `eat.wav`
  - `death.wav`
  - `gameOver.wav`

## How to Run

1. Make sure all image and sound files are in the same directory as `PacMan.java`.
2. Compile the project:
   ```
   javac PacMan.java
   ```
3. Run it (you'll need a `Main` class or equivalent entry point that creates a `JFrame` and adds the `PacMan` panel to it):
   ```
   java Main
   ```

## Project Structure

```
PacMan.java      # Main game logic, rendering, and controls
wall.png         # Wall tile image
*Ghost.png       # Ghost sprite images
pacman*.png      # Pac-Man directional sprites
*.wav            # Sound effect files
```

## Author

Dev.Sahr (Sahr Momoh Solokor) — Computer Science student, University of Makeni (UNIMAK)

## License

This project is for educational purposes.

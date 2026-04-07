# Balance Scale Math Game

A redesigned prototype of the Matific "Fitting Pipes" math game, built as a single page HTML/CSS/JavaScript application for children aged 6–12.

## How to Run

### Option 1: Open Directly (Recommended)

1. Download or clone this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3. No installation, server, or build step required.

### Option 2: Build from Source

This prototype is a self contained single file HTML application. All CSS, JavaScript, and image assets are embedded inline. There are no external dependencies, build tools, or compilation steps.

To "build" from source:

1. Clone this repository:
   ```
   git clone <repository-url>
   cd <repository-folder>
   ```
2. The source code is `index.html`. Open it directly in a browser:
   ```
   open index.html
   ```
   Or on Linux:
   ```
   xdg-open index.html
   ```
   Or simply double click the file in your file manager.



## Features

- **3 difficulty levels** (Easy, Medium, Hard) with progressive unlocking
- **Hidden bonus level** (Whack a Mole math) unlocked after completing all 3 levels
- **Real-time balance scale** with tilt animation reflecting weight difference
- **Drag-and-drop** number tiles onto the scale
- **Auto-check** — the game detects correct answers automatically
- **Hint system** — after 3 wrong attempts, the correct tile is highlighted
- **Achievement system** with collectible avatar rewards
- **Tutorial system** with in game guided walkthrough
- **Sound effects** for correct and wrong answers, achievements, and interactions
- **Progress saving** via localStorage


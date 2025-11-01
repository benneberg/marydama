# MaryDama Checkers / Draughts

MaryDama is a browser-based, AI-integrated checkers (draughts) game built using **HTML, CSS, JavaScript, and TailwindCSS**. It supports multiple variants of the game, allows human vs. human or human vs. AI play, and includes features like move highlighting, undo, and visual themes. 

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Game Variants](#game-variants)
- [Controls & Gameplay](#controls--gameplay)
- [AI Opponent](#ai-opponent)
- [Themes](#themes)
- [Installation](#installation)
- [Usage](#usage)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)

---

## Demo

Open `index.html` in any modern browser.  
No backend setup is required; everything runs client-side.

---

## Features

- Human vs. Human (PvP) and Human vs. AI (PvG)
- Two board variants:
  - **American Draughts** (8x8)
  - **International Draughts** (10x10)
- AI difficulty levels: Easy, Medium, Hard
- Highlight legal moves and multi-capture sequences
- Undo last move(s)
- Move history and debug panel for advanced analysis
- Visual themes: Classic, Greyscale, Ocean
- Coordinate display for easy reference
- Responsive design for mobile and desktop

---

## Game Variants

### American Draughts
- Board size: 8x8
- Pieces: 12 per side
- Men move and capture diagonally forward
- Kings move and capture diagonally one step in any direction
- Captures are mandatory
- Any available capture sequence can be chosen
- A man’s turn ends immediately if it becomes a king during a capture

### International Draughts
- Board size: 10x10
- Pieces: 20 per side
- Men move diagonally forward and capture forward/backward
- Kings are “flying kings” and can move/capture any distance along diagonals
- Captures are mandatory; player must maximize captures
- Tie-breaker: prefer capturing more kings

---

## Controls & Gameplay

- **Click a piece** to select it
- **Click a target square** to move
- **New Game**: restart the board with selected variant and mode
- **Undo**: revert previous move(s)
- **Coords**: toggle display of board coordinates
- **Rules**: view game rules in a modal
- **Theme Selector**: switch visual styles

---

## AI Opponent

- AI powered by **Google Gemini AI** (or fallback random-move generator)
- Difficulty settings:
  - **Easy**: may make mistakes, beginner-friendly
  - **Medium**: plays optimal moves, follows mandatory capture rules
  - **Hard**: grandmaster-level, calculates multi-step strategy
- AI considers full board state, captures, and king priority

---

## Themes

1. **Classic** – yellow & gray traditional board colors  
2. **Greyscale** – neutral gray tones  
3. **Ocean** – cyan/blue theme for a modern look  

---

## Installation

1. Clone or download this repository:

```bash
git clone https://github.com/your-username/marydama-checkers.git
````

2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox, Safari)

No additional dependencies are required besides **internet access** for TailwindCSS and optional AI integration.

---

## Usage

* Select **board variant** (American or International)
* Choose **game mode** (PvP or PvG)
* Select **AI difficulty** if playing against AI
* Play using mouse/touch input
* Undo moves as needed
* Change **themes** on the fly
* View rules and debug information from the control panel

---

## Technical Details

* Built with:

  * **Vanilla JavaScript** for game logic
  * **TailwindCSS** for styling
  * **HTML5/CSS3** for layout and responsive design
* Game logic handles:

  * Legal moves
  * Multi-capture sequences
  * King promotion
  * Game-over detection
* AI moves:

  * Calls Gemini API via `GoogleGenAI`
  * Fallback random moves if AI fails
* Animations:

  * Smooth piece movement
  * Highlight possible moves
* State management:

  * Board state
  * Current player
  * Move history
  * Debug logs

---

## Contributing

---

## License

This project is open-source under the **MIT License**.

---

## Screenshots

---

Enjoy **MaryDama Checkers / Draughts**! Play, analyze, and master your checkers strategy with AI-assisted gameplay.

```

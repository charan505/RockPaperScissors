# Rock Paper Scissors Game 🪨📄✂️

A fun and interactive **Rock Paper Scissors** game built using **HTML, CSS, and JavaScript**. This web game allows the user to play against the computer, keeping track of the score and providing real-time feedback on wins, losses, and draws. It features a clean and modern UI, intuitive gameplay, and responsive design.

---

## Table of Contents

- [Features](#features)  
- [Demo](#demo)  
- [Technologies Used](#technologies-used)  
- [How to Play](#how-to-play)  
- [Project Structure](#project-structure)  
- [Game Logic](#game-logic)  
- [Installation & Usage](#installation--usage)  
- [Future Enhancements](#future-enhancements)  
- [License](#license)  
- [Contact](#contact)  

---

## Features

- **Interactive gameplay:** Click on rock, paper, or scissors to play against the computer.  
- **Dynamic scoring system:** Tracks both the user and computer scores in real-time.  
- **Immediate feedback:** Shows a message indicating whether the user won, lost, or drew the game.  
- **Visual cues:** Changes message background color to green for a win, red for a loss, and default for a draw.  
- **Modern, responsive UI:** Circular buttons for choices with hover effects and a visually appealing scoreboard.  
- **No external libraries required:** Pure HTML, CSS, and JavaScript.  

---

## Demo

![Game Screenshot](screenshot.png)  
*(Replace with an actual screenshot of your game)*

---

## Technologies Used

- **HTML5** – Provides the structure and layout of the game.  
- **CSS3** – Styling, responsive design, and hover effects.  
- **JavaScript (ES6)** – Game logic, score tracking, and interactivity.  

---

## How to Play

1. Open the game in a modern web browser.  
2. Click on one of the three choices: **Rock, Paper, or Scissors**.  
3. The computer will randomly select a choice.  
4. The game will compare the choices and:  
   - **Win:** Green message shows “You win!” with the winning combination.  
   - **Lose:** Red message shows “You lose!” with the winning combination.  
   - **Draw:** Neutral message shows “Game was draw!”  
5. The scoreboard updates automatically after every round.  
6. Continue playing to try and beat the computer!  

---

rock-paper-scissors/
│
├── index.html # Main HTML file containing the game layout
├── eight css.css # CSS styling for the game
├── eight.js # JavaScript logic and game functionality
├── images/ # Folder containing rock, paper, scissors images
│ ├── rock.png
│ ├── paper.png
│ └── scissors.png
└── README.md # Project documentation


---
## Game Logic

The game follows the classic rules of **Rock Paper Scissors**:

- **Rock beats Scissors**  
- **Scissors beats Paper**  
- **Paper beats Rock**

**Implementation Details:**

1. The user's choice is captured via clicking one of the choice buttons.  
2. The computer’s choice is generated randomly using:
```javascript
const options = ["rock", "paper", "scissors"];
const randIdx = Math.floor(Math.random() * 3);
return options[randIdx];

## Project Structure

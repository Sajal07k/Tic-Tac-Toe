# 🎮 Tic-Tac-Toe Game
A simple web-based Tic-Tac-Toe game built using HTML, CSS, and JavaScript. This project demonstrates DOM manipulation, event handling, and game logic implementation in a clean and interactive way.

## 🖥️ Demo
Play the game locally by opening the index.html file in your browser.

## 📁 Project Structure
tic-tac-toe/
│
├── index.html      // Main HTML structure
├── style.css       // Styling (not provided here)
└── app.js          // Game logic and interactivity

## 🚀 Features
* Two-player gameplay (O vs X)
* Automatically checks for a win after every move
* Displays a congratulatory message on winning
* Includes "New Game" and "Reset Game" functionality

## 🔧 How It Works
* The board is a 3x3 grid of buttons.
* Players take turns clicking empty boxes to place their symbol (O or X).
* The game checks for winning combinations after every move.
* Once a player wins, the game shows a message and disables further input.
* "New Game" and "Reset Game" buttons restart the game.

## 📜 Winning Logic
The game checks the following patterns for a win:
* Horizontal: [0,1,2], [3,4,5], [6,7,8]
* Vertical: [0,3,6], [1,4,7], [2,5,8]
* Diagonal: [0,4,8], [2,4,6]
If all three positions in any pattern are the same and not empty, the player with that symbol wins.

## 🛠️ Technologies Used
* HTML5
* CSS3
* JavaScript (ES6)

## 📦 Getting Started
1. Clone this repository or download the source code.
2. Make sure all files (index.html, style.css, app.js) are in the same directory.
3. Open index.html in your browser.
4. Start playing!

## 💡 Future Enhancements
* Add score tracking
* Implement AI for single-player mode
* Improve UI/UX with animations and sound

## 🙌 Author
Hi, I’m Sajal Gupta!
I built this project while learning from a YouTube tutorial to improve my frontend skills.

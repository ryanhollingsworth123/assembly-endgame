# Assembly Endgame

**A small Hangman-style word-guessing game built with React for learning purposes.**  
This project was created to practice React, Vite, and core frontend development concepts such as state management, event handling, and component design.

---

## Demo

**Live Demo:** https://ryanhollingsworth123.github.io/assembly-endgame/

---

## About

Assembly Endgame is a simple interactive game where the player tries to guess a hidden word by selecting letters — similar to *Hangman*. The game tracks correct and incorrect guesses and provides dynamic visual feedback as the player progresses.
---

## Features

✔️ Guess letters to uncover a hidden word.  
✔️ Interactive on-screen keyboard.  
✔️ Dynamic tracking of correct and incorrect guesses.  
✔️ Simple responsive UI built with React.  
✔️ Built with Vite for fast development experience.

---

## Tech Stack

- **Framework:** React  
- **Bundler / Dev Server:** Vite  
- **Styling:** CSS  
- **JavaScript:** ES6+  
- **Package Manager:** npm / Yarn

---

## Project Structure

assembly-endgame/
├── public/ # Static assets and HTML template
├── src/ # React source files
│ ├── App.jsx # Main application component
│ ├── components/ # UI components
│ ├── styles/ # CSS styles
│ └── utils/ # Utility functions
├── .gitignore
├── index.html
├── package.json # Scripts & dependencies
├── vite.config.js # Vite configuration
└── README.md

---

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/ryanhollingsworth123/assembly-endgame.git
Navigate into the project directory

cd assembly-endgame
Install dependencies

npm install
Start the development server

npm run dev
Open your browser and go to:

http://localhost:5173/

How to Play:

Start the game — a hidden word will be selected.

Click letters on the on-screen keyboard to guess.

Correct guesses reveal those letters in the word.

Incorrect guesses are tracked and reduce the remaining chances.

Guess all letters before running out of chances to win!

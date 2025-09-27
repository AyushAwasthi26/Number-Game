NUMBER GUESSING GAME: Test Your Luck and Logic!

A fun and interactive number guessing game where players attempt to guess a randomly generated number between 1 and 100. Challenge yourself with only 10 attempts and see if you can crack the code!

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)


📋 Table of Contents:

- [📸 Screenshots](#-screenshots)
- [🎮 About the Game](#-about-the-game)
- [✨ Features](#-features)
- [💻 Tech Stack](#-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [🎯 How to Play](#-how-to-play)
- [🔧 Code Structure](#-code-structure)
- [📜 License](#-license)


## 📸 Screenshots:
<img width="1917" height="974" alt="image" src="https://github.com/user-attachments/assets/b3dde854-5800-459c-9a88-0ae863ec75e8" />
<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/805c80be-19fb-4ecb-ae2b-05a3a7ef3f65" />
<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/4310ca6a-c45e-4b49-9502-1cc2a3068024" />


## 🎮 About the Game:

The Number Guessing Game is a classic web-based game that challenges players to guess a randomly generated number within a limited number of attempts. Built with vanilla JavaScript, HTML, and CSS, this game demonstrates fundamental programming concepts like random number generation, user input validation, and DOM manipulation.

Here's how it works:

You enter your guess: Using a simple input field, you provide a number between 1 and 100.

Our game engine processes: The JavaScript logic compares your guess with the randomly generated target number.

We give you instant feedback: The game tells you if your guess is too high, too low, or exactly right, helping you narrow down the correct answer.

The project demonstrates clean code structure and interactive web development, making it perfect for learning fundamental JavaScript concepts.

## ✨ Features:

Interactive Gameplay: Real-time feedback system that guides players with each guess.

Input Validation: Robust validation ensuring only valid numbers between 1-100 are accepted.

Attempt Tracking: Visual display of previous guesses and remaining attempts.

Smart Feedback System: Clear hints telling players if their guess is too high or too low.

Game Reset Functionality: Easy restart option to play multiple rounds.

Responsive Design: Clean, user-friendly interface that works across devices.

## 💻 Tech Stack:

Frontend: HTML5, CSS3, JavaScript (ES6+)

Frameworks & Libraries: Inter Font Family, Custom CSS

Styling: Modern typography with clean, accessible design.

Backend: Pure client-side logic with no server requirements

## 🚀 Getting Started:

To get the Number Guessing Game running on your local machine, follow these simple steps.

Prerequisites
You'll need a modern web browser and optionally a text editor for modifications.

Installation:

Clone the repository to your local machine:

git clone [https://github.com/YourUsername/number-guessing-game.git](https://github.com/YourUsername/number-guessing-game.git)

Navigate to the project directory:

cd number-guessing-game

Open the game:

Simply double-click on index.html or open it in your preferred web browser.

That's it! No build process, dependencies, or server setup required.

Contributing:

To contribute to the project, make your changes and then follow these Git commands:

Stage your changes:

git add .

Commit your changes with a descriptive message:

git commit -m "feat: added difficulty levels"

Push your changes to the remote repository:

git push origin main

(Note: Replace main with the name of your branch if you are working on a different one).

## 🎯 How to Play:

Game Rules:

Start the Game: Open the HTML file in your browser

Make Your Guess: Enter a number between 1 and 100 in the input field

Submit: Click the "Submit guess" button

Read the Feedback: The game will tell you if your guess is too high, too low, or correct

Keep Trying: You have 10 total attempts to find the right number

Track Progress: Watch your previous guesses and remaining attempts

Win or Lose: Successfully guess the number or run out of attempts

Play Again: Click "Start new Game" to play another round

## 🔧 Code Structure:

Key Functions:

validateGuess(guess): Ensures user input is valid (number between 1-100)

checkGuess(guess): Compares user guess with the random number and provides feedback

displayGuess(guess): Updates the UI with the current guess and remaining attempts

displayMessage(message): Shows feedback messages to the user

endGame(): Handles game over scenario and enables restart functionality

newGame(): Resets all game variables and starts a fresh round

Key Variables:
- randomNumber: The target number to guess
- prevGuess: Array storing all previous guesses
- numGuess: Counter for current attempt number
- playGame: Boolean flag controlling game state

## 👥 Project Team:

This project was developed as a learning exercise in vanilla JavaScript and DOM manipulation.

-->Developer [Full Stack Developer]

Focused on creating an engaging, interactive experience that demonstrates core JavaScript concepts while maintaining clean, readable code.

## 📜 License
This project is licensed under the MIT License - see the LICENSE.md file for details.

[🔝 Back to Top](#-table-of-contents)

🪨📄✂️ Rock • Paper • Scissors

A Simple JavaScript Game (Web Version)

Welcome! This project is a lightweight, responsive, browser-based Rock–Paper–Scissors game. It uses plain HTML, CSS, and vanilla JavaScript to deliver a clean interactive experience with smooth animations and a friendly UI.

⸻

🎯 Overview

This project lets users play Rock–Paper–Scissors against the computer. Once the user chooses an option, both sides animate their “hands,” and a result is displayed based on the classic rules:
	•	Rock beats Scissors
	•	Paper beats Rock
	•	Scissors beats Paper
	•	Same choice → Draw

All logic, assets, gameplay flow, and animations are defined within three simple files:
	•	HTML structure: index.html  ￼
	•	Game logic: script.js  ￼
	•	Styles & animations: styles.css  ￼

⸻

🧩 Features

✔️ Fully animated gameplay

When a round begins, the user and computer “hands” shake using custom CSS animations before revealing their selections.

✔️ Instant interaction

Player inputs are captured through click events, triggering the game sequence with a small delay for animation syncing.

✔️ Clean separation of concerns
	•	HTML handles layout
	•	CSS handles all visual styling & responsiveness
	•	JavaScript handles all logic and event flow

✔️ Mobile responsive

The CSS includes a media query that reduces image sizes and optimizes spacing for smaller screens.

✔️ No external JavaScript libraries

Everything is built using native browser APIs.

⸻

🗂️ File Architecture

/
│── index.html
│── styles.css
│── script.js
│── images/
│     ├── rock.png
│     ├── paper.png
│     ├── scissors.png
│     └── githubLogo.svg


⸻

📄 How It Works

1. Game Layout (index.html)

The HTML defines:  ￼
	•	The result display area
	•	Animated user & CPU hand images
	•	Clickable option buttons (rock/paper/scissors)
	•	A (non-functional) GitHub link button

Everything sits inside a centered container with minimal markup.

⸻

2. Game Logic (script.js)

The logic follows a simple sequence:  ￼

a. Setup
The script selects all interactive DOM elements:

const optionImages = document.querySelectorAll(".option_image");
const container = document.querySelector(".container");
const result = document.querySelector(".result");
const userResultImg = document.querySelector(".user_result img");
const computerImgUrl = document.querySelector(".cpu_result img");

It then defines:
	•	A list of possible turns (rock/paper/scissors)
	•	A mapping of winning combinations

b. Handling User Input
Clicking an option triggers:
	1.	startGame() – shows “wait…”, adds animations
	2.	A short delay
	3.	endGame() – runs winner logic and resets animations

c. Determining the Winner
The code compares:

let resultArr = [computerSelection, userSelection];

It then finds a matching rule in the combinations array, displaying either:
	•	"you wins"
	•	"computer wins"
	•	"Game Draws"

⸻

3. Styling & Animations (styles.css)

The stylesheet:  ￼
	•	Imports Google Font (“Poppins”)
	•	Applies a white card UI with a subtle shadow
	•	Adds shake animations (@keyframes userShake, @keyframes cpuShake)
	•	Defines colors, transitions, hover states, and responsive breakpoints
	•	Disables option clicks while the game is “in progress”

⸻

🚀 Running the Project

No build step is needed.

Open locally
	1.	Clone or download the folder.
	2.	Open index.html in any modern browser.
	3.	Click on Rock, Paper, or Scissors to play.

Requirements
	•	Any modern browser (Chrome, Firefox, Safari, Edge)
	•	JavaScript enabled

⸻

📦 Customization

You can easily extend or adjust:

🔊 Add sound effects

Trigger audio clips in startGame() or checkWinner() based on user or computer wins.

🎨 Change the theme

Modify colors, spacing, and animations in styles.css to match your brand or design taste.

🤖 Make the computer “smart”

Replace Math.random() with weighted logic, patterns, or difficulty levels.

🏆 Add scoring

Track wins/losses/draws and display a scoreboard. You could even store stats in localStorage so they persist across page reloads.

⸻

🧪 Known Limitations
	•	The GitHub link button currently points to a different project (Memory Matrix) instead of this repository.  ￼
	•	The winning-combination mapping works but could be simplified with more compact logic.  ￼
	•	Only three turns are supported (Rock, Paper, Scissors). Adding more options (e.g., “Lizard” and “Spock”) would require changes to both the turn data and the winner-determination logic.

⸻

🗺️ Possible Improvements
	•	Add a best-of-3 or best-of-5 match mode.
	•	Show an animation or highlight for the winning choice each round.
	•	Add a start screen and a reset button for improved UX.
	•	Make the GitHub button link to the actual repository for this game.  ￼

⸻

📜 License

This project is free to use, modify, and extend for personal or educational purposes.
Feel free to adapt it as a learning project, coding challenge, or starter template for more advanced browser games.
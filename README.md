<h1 align="center">Coding Quiz</h1>

<p align="center">A timed, multiple-choice quiz on JavaScript fundamentals with a high-score board.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css&amp;logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript">
</p>

<p align="center"><a href="https://christianjkrantz.github.io/coding-quiz/"><strong>Live Demo</strong></a></p>

<p align="center">
  <img src="docs/screenshot-start.png" alt="Coding Quiz start screen" width="420">
  <img src="docs/screenshot-question.png" alt="A quiz question showing the wrong answer in red, the correct answer in green and the countdown timer" width="420">
</p>

## Features

- 7 multiple-choice questions on JavaScript fundamentals
- 75-second countdown timer. Every wrong answer costs 10 seconds, and the timer turns red in the final 10 seconds.
- Instant on-page feedback after each answer. A wrong answer also highlights the correct one.
- The game ends when every question is answered or the timer reaches 0
- Your score is the time you have left. Save it with your initials.
- High-score board sorted from best to worst, keeping the top 10 in `localStorage`
- Clear the high scores or play again at any time
- Keyboard-friendly, with a responsive layout for desktop and mobile

## Built With

- HTML, CSS and JavaScript (no libraries)

## Running Locally

No build step is needed.

1. Clone the repo:
   ```bash
   git clone https://github.com/ChristianJKrantz/coding-quiz.git
   ```
2. Open `index.html` in your browser.

## Author

**Christian Krantz**: [Portfolio](https://christianjkrantz.github.io/) · [LinkedIn](https://www.linkedin.com/in/christianjkrantz) · [GitHub](https://github.com/ChristianJKrantz)

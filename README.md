# BrainQuest

<img width="947" height="435" alt="image" src="https://github.com/user-attachments/assets/17f6ffb3-554a-4235-acc3-56ad330ba344" />


## Games

- **Wordle** — Guess the 5-letter word in up to 6 attempts.
- **Chess** — Play a simple two-player chess game with legal piece movement and move highlighting.
- **Image Puzzle** — Upload an image, choose the difficulty, and drag scattered jigsaw pieces into the correct positions.
- **Typing Test** — Type a passage for 30 seconds and track your WPM and accuracy.

## Technologies

- HTML5
- CSS3
- JavaScript
- GitHub Pages

No frameworks or build tools are required.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/tayvol/brainquest.git
cd brainquest
```

Then open `index.html` in a browser.

For the best local development experience, you can also use VS Code with the Live Server extension.

## Live Website

The project is designed to be deployed with **GitHub Pages**.

Repository:  
https://github.com/tayvol/brainquest

## Project Structure

```
brainquest/
├── index.html
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── games.js
│   └── storage.js
└── README.md
```

## How It Works

The main page presents the available games. Selecting **Play** opens the chosen game inside a modal window.

Each game is implemented in JavaScript:

- `games.js` contains the game logic.
- `app.js` controls the application interface and game launching.
- `storage.js` handles saved game statistics.
- `style.css` contains the complete visual design, responsive layout, animations, and game styling.

## Author

**Tanaya Bedase**

- GitHub: https://github.com/tayvol
- LinkedIn: https://www.linkedin.com/in/tanayabedase22/

## License

This project is created for educational and personal portfolio purposes.

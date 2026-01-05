# Simon Game 🎮

A classic memory skill game built for the web. The game creates a sequence of tones and lights and requires the user to repeat the sequence. If the user succeeds, the series becomes progressively longer and more complex.

## 🌟 Features

* **Interactive Interface:** Responsive button animations and click handling.
* **Audio Feedback:** Distinct sounds for each color and a specific sound for "Game Over."
* **Dynamic Difficulty:** The game pattern increases by one step after every successful round.
* **Game State Management:** Tracks levels and resets automatically upon failure.
* **Retro Design:** Uses the "Press Start 2P" Google Font for an arcade aesthetic.

## 🛠️ Tech Stack

* **HTML5:** Structure and layout.
* **CSS3:** Styling, animations (`.pressed` class), and layout.
* **JavaScript (ES6):** Game logic, array manipulation, and random sequence generation.
* **jQuery:** Simplified DOM manipulation and event handling.

## 📂 Project Structure

```text
Simon-Game/
├── index.html      # Main HTML file
├── styles.css      # CSS styling
├── game.js         # Game logic
├── README.md       # Project documentation
└── sounds/         # Audio files
    ├── green.mp3
    ├── red.mp3
    ├── yellow.mp3
    ├── blue.mp3
    └── wrong.mp3
🚀 How to Run Locally
Clone or Download this repository.

Ensure you have the sounds folder with the necessary .mp3 files in the same directory as index.html.

Open index.html in any modern web browser (Chrome, Firefox, Safari).

🕹️ How to Play
Open the game in your browser.

Press any key on your keyboard to start the game.

Watch the button that flashes and listen to the sound.

Click the same button.

If you are correct, the game will add another step to the sequence.

Continue repeating the pattern.

If you click the wrong button, the background turns red, a "Game Over" sound plays, and you must press a key to restart.

🔮 Future Improvements
Add a "Start" button for mobile compatibility (currently relies on keyboard press).

Add a High Score tracker using LocalStorage.

Make the layout fully responsive for smaller mobile screens.

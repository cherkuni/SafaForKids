# 🌍 WorldSorter: Language Match Game

**[🎮 Play the Game Now!](https://cherkuni.github.io/SafaForKids/)**

A fast-paced, interactive drag-and-drop educational game designed to help users learn basic vocabulary across 12 different languages. Match the word to the correct country flag, build your streak, and discover new words across 15 distinct themes!

## ✨ Features

*   **Zero Dependencies:** The entire game runs from a single `index.html` file. No build steps, no complex setups.
*   **Physics-Based Drag & Drop:** Smooth, satisfying card-dragging mechanics optimized for both desktop and mobile devices.
*   **12 Languages:** English, Spanish, French, German, Italian, Japanese, Hebrew, Arabic, Russian, Hindi, Korean, and Chinese.
*   **15+ Themes:** Practice greetings, numbers, colors, animals, food, and more.
*   **Native Scripts & Transliterations:** Hover over foreign scripts (like Japanese or Arabic) to see the phonetic English pronunciation.
*   **Progression System:** Features an XP/Level bar, streak announcements, and dynamic visual feedback for correct and incorrect answers.
*   **Generative Audio:** Built-in Web Audio API sound effects for successes, errors, and streak milestones (no external audio files needed).

## 🚀 How to Play

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Click **Start Game**.
4. Drag the active word card into the circular drop zone of the correct language's flag.
5. If you make a mistake, the target flag will gray out, and you can try again (but you'll lose your current streak!).
6. Click the **Theme** button at the top to switch categories at any time.

## 🛠️ Customization

Want to add new words or languages? It's easy! 
Open `index.html` in any text editor and locate the `GAME_DATA` and `FLAGS` objects in the `<script>` section. You can easily add new themes or language codes without needing to change any of the core game logic.

## 📄 License

This project is open-source and free to use for educational and personal projects.

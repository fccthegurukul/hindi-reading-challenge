# 🎤 Reading Battle Arena (Hindi)

![Project Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Language](https://img.shields.io/badge/Language-Hindi%20%7C%20English-blue)
![UI](https://img.shields.io/badge/UI-Dark%20Neon-purple)

A gamified web application designed for classrooms to test and improve students' **Hindi reading skills, pronunciation, and speed**. 

Built with a "Game Show" aesthetic, this tool allows teachers to evaluate students in a high-energy, interactive environment with sound effects, streaks, and live leaderboards.

## 🌟 Key Features

* **Dark Neon UI:** "Gaming-style" interface that looks great on projectors and smartboards.
* **Two Game Modes:**
    * **🔥 Word Rapid Fire:** Fast-paced single word reading (2 seconds per word).
    * **📜 Sentence Flow:** Full paragraph reading with a 1-10 rating system.
* **Audio Feedback:** Instant "Correct", "Wrong", and "Power-up" sounds.
* **Streak System:** Animations (🔥, 🚀) pop up when a student gets 5+ correct answers in a row.
* **Live Leaderboard:** Tracks scores and ranks students automatically.
* **CSV Export:** Download the final class results to Excel with one click.
* **Customizable Data:** Easily edit the JSON data to add your own words or stories.

## 🎮 How to Play (Teacher's Controls)

This game requires a **Teacher/Moderator** to control the scoring while the student reads from the screen.

### Mode 1: Word Rapid Fire (Shabd)
* **Student:** Reads the word displayed on the screen.
* **Teacher Controls:**
    * Press **`A`** : ✅ Correct Pronunciation (+1 Point)
    * Press **`F`** : ❌ Wrong/Skipped (-0.5 Point)

### Mode 2: Sentence Flow (Vakya)
* **Student:** Reads the full sentence/paragraph.
* **Teacher Controls:**
    * Press **`1` to `9`** : Rate the reading quality (Score 1-9).
    * Press **`0`** : Perfect Score (10 Points).

## 🚀 How to Run

1.  **Download:** Clone this repository or download the ZIP file.
2.  **Run:** Simply double-click the `index.html` file. It works in any modern browser (Chrome, Edge, Firefox).
3.  **No Internet Required:** The game runs completely offline once downloaded.

## ⚙️ Customization (Add Your Own Content)

You can change the words and paragraphs easily!

1.  Open the `.html` file in any text editor (Notepad, VS Code).
2.  Scroll down to the `WORD_PACKS` or `SENTENCE_PACKS` section in the JavaScript.
3.  Edit the text inside the quotes:
    ```javascript
    const WORD_PACKS = [
        {
            id: "my_new_round",
            title: "My Custom Words",
            content: "Write your words here separated by spaces"
        }
    ];
    ```
4.  Save and refresh the browser.

## 🛠️ Technologies Used

* **HTML5**
* **Tailwind CSS** (via CDN for styling)
* **Vanilla JavaScript** (Game Logic & Audio API)
* **Animate.css** (Animations)

## 📄 License

This project is open-source and free to use for educational purposes.

---
*Created for making Hindi learning fun!* 🚀

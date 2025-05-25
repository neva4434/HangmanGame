# Hangman Game 🎮 (JavaFX)

This project is a graphical version of the classic "Hangman" game developed using JavaFX. Players can register with a username and password, select a difficulty level, and guess randomly selected words. Game results (win/lose) are saved in a `results.txt` file.

## ✨ Features

- JavaFX-based user interface
- Simple user registration and login (stored temporarily in memory)
- Difficulty level selection (Easy, Medium, Hard)
- Random word selection from `words.txt`
- Hangman drawing with Canvas
- Win/Lose result tracking saved in `results.txt`
- Option to return to main menu or play again

## 📁 Project Structure
Hangman/
├── src/
│   └── main/
│       ├── java/com/example/hangman/
│       │   ├── HelloApplication.java
│       │   ├── GameController.java
│       │   ├── LoginController.java
│       │   └── HelloController.java
│       └── resources/com/example/hangman/
│           ├── hello-view.fxml
│           ├── game-view.fxml
│           ├── login-view.fxml
│           └── words.txt
├── pom.xml
└── results.txt

## 📌 Requirements

- Java 17 or above
- JavaFX SDK
- IntelliJ IDEA (recommended with Scene Builder plugin)

## 🚀 How to Run

1. **Open the project** in IntelliJ IDEA or your preferred IDE.
2. **Set up JavaFX** in your project structure and VM options.
3. **Run `Main.java`** to start the application.

## 🧪 How to Play

1. Register with a username and password on the login screen.
2. Select a difficulty level (Easy, Medium, Hard).
3. Start the game and guess the word one letter at a time.
4. After the game ends, see the result and choose to play again or return to the menu.

## 📝 About the Files

- `words.txt`: A plain text file containing words used in the game (one word per line, lowercase).
- `results.txt`: Stores usernames and their game outcomes. Example:
alice - WON
bob - LOST

## 👤 Developer

- 💻 Ayşe Neva Ağca — Student ID: 23040102041

# Tic Tac Toe Android App

A simple two-player **Tic Tac Toe (XO)** game built in Java using **Android Studio**. This app uses a `GridLayout` and `Button` widgets for interaction and logic processing within a `MainActivity`.

---

## 🧩 Features

- Classic 3x3 Tic Tac Toe game
- Two-player mode (Player 1: X, Player 2: O)
- Game detects winner or draw
- Auto-reset after game ends
- Simple and clean UI layout

---

## 📷 Screenshots

*(Add emulator screenshots of your app here for better presentation)*

---

## 🛠️ Tech Stack

- **Language**: Java
- **Framework**: Android SDK
- **Layout**: LinearLayout + GridLayout
- **IDE**: Android Studio

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-android.git
Open the project in Android Studio.

Let Gradle sync and build the project.

Run the app on an emulator or physical device.

📁 File Structure
swift
Copy
Edit
app/
├── java/com/example/tictactoegame/
│   └── MainActivity.java
├── res/layout/
│   └── activity_main.xml
└── AndroidManifest.xml
🧠 Game Logic
Uses a flag (0 or 1) to alternate between players.

Stores button values as strings to check for win conditions.

Uses Toast to display results and resets the board after each match.


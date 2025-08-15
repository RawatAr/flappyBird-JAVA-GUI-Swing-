🐦 Flappy Bird Clone in Java (Swing)

A clean, lightweight recreation of the classic Flappy Bird game — built entirely in Java using Swing.

📑 Table of Contents

Features

Tech Stack

Screenshots

Installation & Running

How to Play

Project Structure

Contributing

License

Acknowledgments

✨ Features

Classic Gameplay — Same addictive mechanics as the original.

Dynamic Obstacles — Pipes appear at random heights each time.

Score Tracking — Earn points for every set of pipes you pass.

Quick Restart — Spacebar restarts the game after a “Game Over.”

Simple Controls — Just one button to play.

🛠 Tech Stack

Language: Java

GUI Library: Swing

🖼 Screenshots
Game Screen	Description

	Background setting the scene

	The bird navigating pipes

/
	The main obstacles
💻 Installation & Running

Make sure Java JDK (or OpenJDK) is installed on your system.

git clone https://github.com/RawatAr/flappyBird-JAVA-GUI-Swing-.git
cd flappyBird-JAVA-GUI-Swing-
javac *.java
java App

🎮 How to Play

Spacebar → Makes the bird jump.

Avoid hitting the pipes or the ground.

Each pipe gap you pass increases your score.

Press Spacebar after Game Over to restart.

📂 Project Structure
flappyBird-JAVA-GUI-Swing-/
├── App.java           – Main entry point; sets up the game window
├── FlappyBird.java    – Game loop, rendering, collisions, and controls
├── flappybirdbg.png   – Background image
├── flappybird.png     – Bird sprite
├── toppipe.png        – Top pipe image
└── bottompipe.png     – Bottom pipe image

🤝 Contributing

Fork the project

Create your branch:

git checkout -b feature/AmazingFeature


Commit changes:

git commit -m "Add some AmazingFeature"


Push the branch:

git push origin feature/AmazingFeature


Open a Pull Request

📜 License

This project is under the MIT License — see LICENSE for details.

🙌 Acknowledgments

The original Flappy Bird by Dong Nguyen for inspiring this clone

The Java & open-source community for resources and guidance

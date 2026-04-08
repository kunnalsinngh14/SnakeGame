# 🐍 Classic Snake Game (Java Swing)

A lightweight, desktop-based implementation of the legendary Snake Game. This project showcases the use of **Java Swing** and **AWT** to create a responsive, event-driven application focused on real-time logic and 2D graphics rendering.

## 🚀 Project Overview
This project serves as a demonstration of core software engineering principles, specifically handling real-time state updates, user input processing, and coordinate-based collision detection. It was developed as part of my portfolio to highlight my proficiency in **Java** and **Object-Oriented Programming (OOP)**.

## ✨ Key Features
* **Grid-Based Movement**: Implements a precise coordinate system using a 10px `DOT_SIZE` for consistent snake behavior.
* **Real-Time Game Loop**: Powered by `javax.swing.Timer` to manage game speed and frame refreshes.
* **Collision Detection Engine**: 
    * **Self-Collision**: Detects if the snake head crosses its own body coordinates.
    * **Boundary Detection**: Triggers Game Over if the snake hits the frame walls.
* **Dynamic Graphics**: Uses `Graphics` and `Toolkit.sync()` to render sprites and text smoothly without flickering.
* **Intuitive Controls**: Integrated `KeyAdapter` to handle arrow key inputs while preventing illegal 180-degree turns.

## 🛠️ Technical Stack
* **Language**: Java (JDK 8+)
* **GUI Framework**: Java Swing
* **Graphics API**: Abstract Window Toolkit (AWT)
* **Design Pattern**: Model-View-Controller (MVC) approach by separating Game Logic (`Board`) from the Application Window (`SnakeGame`).

## 📂 Project Structure
```text
snakegame/
├── icons/
│   ├── apple.png        # Randomized target sprite
│   ├── dot.png          # Body segment sprite
│   └── head.png         # Directional head sprite
├── Board.java           # Core Game Engine (Logic, Timers, Physics)
└── SnakeGame.java       # Main entry point and Frame configuration
🎮 Getting Started
Prerequisites
Java Development Kit (JDK) installed.

An IDE (IntelliJ, Eclipse, VS Code) or terminal access.

Installation & Execution
Clone the repository:

Bash
git clone [https://github.com/kunnalsinngh14/Snake-Game-Java.git](https://github.com/kunnalsinngh14/Snake-Game-Java.git)
Navigate to the source folder:

Bash
cd snakegame
Compile the code:

Bash
javac snakegame/*.java
Run the application:

Bash
java snakegame.SnakeGame
⌨️ Controls
Arrow Keys: Use UP, DOWN, LEFT, and RIGHT to navigate.

Goal: Consume apples to grow your snake while avoiding the boundaries and your own tail.

Developed by Kunal Singh — B.Tech Computer Science (AI/ML) @ RV University.
🐦 Flappy Bird – Java OOPS Edition

A simple yet fully functional clone of the popular "Flappy Bird" game, written entirely in *Java* using *Object-Oriented Programming* principles and *Swing* for the GUI.

---

🎮 Game Overview

This game simulates the behavior of a Flappy Bird navigating through green pipes. The goal is to keep the bird flying by making it jump between obstacles without hitting the pipes or the ground.

How to Play:

- *Start the game* by clicking anywhere or pressing *Space*
- Tap *Space* repeatedly to make the bird "flap" upward
- Avoid hitting the *top and bottom pipes, or the **ground*
- *Score* increases by 1 each time the bird successfully passes between two pipes

If the bird collides with an obstacle, the game displays a *Game Over* screen.

---

🧠 OOPS Concepts Used

This project has been thoughtfully structured using key Object-Oriented Programming principles:

- ✅ *Encapsulation* – Game data is wrapped within logical classes (Bird, Pipe, etc.)
- ✅ *Inheritance* – Uses Java's event-listener inheritance model
- ✅ *Polymorphism* – Through interface implementations (ActionListener, KeyListener, MouseListener)
- ✅ *Abstraction* – Game logic, rendering, and event handling separated cleanly
- ✅ *Modularity* – UI rendering, collision detection, and physics split into independent responsibilities

---

🧱 Class Structure

Core Class: FlappyBird
- Acts as the *Game Controller*
- Manages game state, input, score, and rendering
- Contains logic for:
  - Gravity and jumping
  - Collision with pipes
  - Adding and removing pipe obstacles
  - Display messages like "Game Over" and score count

---

Supporting Class: Renderer
- Extends JPanel
- Overrides paintComponent(Graphics g)
- Delegates drawing to the main FlappyBird instance
- Controls screen refresh and render cycles

---

System Interfaces Implemented:
- ActionListener – for game loop ticks (Timer)
- MouseListener – for mouse-based jumping
- KeyListener – for keyboard-based input (jump using *Space*)

---

📁 Project Folder Layout


FlappyBird/
├── FlappyBird.java          # Main game logic, event handling
├── Renderer.java            # Custom JPanel for rendering
├── Resources/               # (Optional) Fonts, images, audio
└── README.md                # This file


---

🖼 Screenshots (SS)
<p align = "center">
<img src="https://github.com/user-attachments/assets/95b8bf45-0ee6-4481-bbfa-c9ec624175f4" alt="click to start" width="30%">
<img src="https://github.com/user-attachments/assets/06710c80-e23a-4fe8-8161-952681df5b49" alt="Gameplay" width="30%">
<img src="https://github.com/user-attachments/assets/4637cee4-91ab-4d7d-95d3-6339ff438248" alt="Game over" width="30%">
</p>
---

---

🎥 Gameplay Video
https://github.com/aadyagupta44/Flappy-Bird/releases/tag/demovideo


---

## 🔨 Tools Used

- *Java SE* 8+
- *Swing GUI* Framework
- *Java AWT* (Graphics, Rectangle, Timer)
- IDE: Any Java IDE such as IntelliJ, Eclipse, or VS Code

---

## 🧪 How to Run

1. Open the project in your preferred Java IDE
2. Run the FlappyBird class
3. Game window will launch and be ready for interaction

Make sure all files (FlappyBird.java, Renderer.java) are in the same package (e.g., flappyBird).

---

## 📚 Concepts Practiced

- Event-driven programming
- Real-time rendering with Timer
- Collision detection using Rectangle.intersects()
- Game physics simulation
- Custom component rendering using paintComponent()

---

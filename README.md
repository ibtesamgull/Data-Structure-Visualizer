# 🚀 DSA Visualizer

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![GUI](https://img.shields.io/badge/GUI-Java_Swing-blue?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open_Source-Yes-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

A professional, interactive desktop application built in Java that brings Data Structures and Algorithms to life. 

DSA Visualizer bridges the gap between theoretical concepts and practical understanding by providing real-time, step-by-step graphical representations of both **Linear** and **Non-Linear** data structures. It is designed to help developers, students, and educators instantly see how elements are stored, manipulated, and traversed under the hood.

---

## ✨ Core Features

* **🔐 Secure Access:** Integrated authentication system (`LoginFrame`) to manage user sessions.
* **🗂️ Linear Data Structures:**
  * **Stack:** Visual representation of `Push`, `Pop`, and `Peek` operations (LIFO mechanism).
  * **Queue:** Real-time visualization of `Enqueue` and `Dequeue` operations (FIFO mechanism).
  * **Linked List:** Interactive node creation, linking, deletion, and visual traversal.
* **🌳 Non-Linear Data Structures:**
  * **Trees:** Dynamic node insertion, branching, and hierarchical data rendering.
  * **Graphs:** Visual rendering of vertices and edges to demonstrate complex network structures.
* **🎨 Seamless GUI:** Clean, intuitive, and responsive interface built entirely with native Java Swing components.

---

## 📸 Screenshots & Demos

*(Replace these placeholders with actual screenshots or GIFs of your application in action to make your repository stand out.)*

| User Login & Menu | Linear Structures (Stack/Queue) | Non-Linear Structures (Trees/Graphs) |
| :---: | :---: | :---: |
| ![Menu Placeholder](https://via.placeholder.com/250x150.png?text=Add+Main+Menu+Image) | ![Linear Placeholder](https://via.placeholder.com/250x150.png?text=Add+Stack/Queue+GIF) | ![Non-Linear Placeholder](https://via.placeholder.com/250x150.png?text=Add+Tree/Graph+GIF) |

> **GitHub Expert Tip:** Use a screen recording tool to capture 5-second GIFs of your nodes animating, and drop them in this section. Visual projects need visual readmes!

---

## 📂 Project Structure

The project follows a modular, object-oriented architecture ensuring clean separation of concerns between different visualization components:

```text
DS VISUALIZER/
├── src/
│   ├── DataStructureVisualizer.java       # Main Entry Point
│   ├── LoginFrame.java                    # Authentication UI
│   ├── MainMenuFrame.java                 # Dashboard UI
│   ├── LinearDSFrame.java                 # Linear DS Routing
│   ├── NonLinearDSFrame.java              # Non-Linear DS Routing
│   ├── StackVisualizerFrame.java          # Stack Logic & Canvas
│   ├── QueueVisualizerFrame.java          # Queue Logic & Canvas
│   ├── LinkedListVisualizerFrame.java     # Linked List Logic & Canvas
│   ├── TreeVisualizerFrame.java           # Tree Logic & Canvas
│   └── GraphVisualizerFrame.java          # Graph Logic & Canvas
└── out/artifacts/untitled_jar/            # Compiled Executable
    └── DSA VISUALIZER.jar<!-- Snake Game Repo View -->

<div align="center">
  <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
</div>

# 🕹️ Interactive Logic Quest: A QA & Product Management Sandbox 

## 📖 Project Overview
The **Interactive Logic Quest** is a web-based, gamified onboarding application designed to teach foundational Python syntax and logic. Built with a "Dark Neon" aesthetic, the application scales from guided terminal inputs to complex, grid-based spatial puzzles. 

This project serves as a practical sandbox to demonstrate **Quality Assurance (QA) methodologies**, **Software Development Life Cycle (SDLC) management**, and **Product Iteration**.

## 🎯 Product Management & SDLC Focus (CAPM)
As the Project Lead, I managed the scope and iterative development of this application:
* **Requirements Gathering:** Defined user personas (beginners/students) to ensure the UI provided explicit, guided instruction to minimize user friction.
* **Iterative Scaling:** Expanded the MVP from a basic text terminal into a multi-phase application featuring CSS animations, Web Audio API integration, and a 2D-array movement engine.
* **Feature Pivoting:** Successfully pivoted the visual layout from a standard retro terminal to a responsive split-screen "Action/Terminal" viewport to improve user retention.

## 🐛 QA Testing & Defect Resolution
During the testing phase of the Level 4 Grid Maze, I conducted exploratory testing and identified a critical procedural generation defect. 

* **The Defect:** The level generator created an unsolvable maze, completely boxing the player entity in with "Wall" arrays, halting all user progression.
* **Root Cause:** The random generation logic lacked an unbroken path validation check.
* **The Resolution (Interactive Workaround):** Instead of rewriting the entire generation engine, I conceptualized and implemented a new interactive game mechanic: **"Wall Hacking."** * **Implementation:** Added an asynchronous double-tap/click event listener allowing users to permanently mutate the state of adjacent "Wall" tiles into "Path" tiles, triggering a CSS shatter animation and audio cue. This turned a game-breaking bug into a highly engaging user feature.

## 💻 Tech Stack & Features
* **Environment:** HTML5, CSS3, Vanilla JavaScript (Built via Base44 AI Engine).
* **State Management:** 2D Array mapping for grid logic and collision detection.
* **Performance:** Debounced input validation to prevent browser memory leaks and infinite loops during text entry.
* **Media:** Integrated HTML5 Video and Web Audio API for immersive feedback.

## 🚀 Play the Game
[Insert your GitHub Pages Link Here]

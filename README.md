# PatroArcade Project

Welcome to the PatroArcade superproject! This repository is the main entry point for a system designed to modernize physical arcade machines by integrating digital games with a web platform.

## 📖 Project Structure

This repository uses **Git Submodules** to manage the different components of the system. The main project points to specific versions of the following sub-repositories:

* **`/PatroArcade-API`**: The backend RESTful API for user management, game data, and real-time communication.
* **`/PatroArcade-WebServer`**: The server-side rendering web application for user-facing pages.
* **`/PatroArcade-GodotExtension`**: The Godot Engine project containing the core integration extension and a sample game.

## 🚀 Getting Started

To clone this project and its submodules, run:

```bash
git clone --recurse-submodules https://github.com/luisfpatrocinio/PatroArcade.git
cd PatroArcade
```
# 🏙️ CityOS Core — Production Build

A high-performance, responsive **2.5D Isometric City Builder Simulation Engine** built with React. This project demonstrates advanced state management, autonomous game loops, and persistent data handling without the need for heavy external game engines.

---


## ✨ Key Technical Features

*   **2.5D Isometric Grid:** Optimized rendering using pure CSS 3D transforms (`preserve-3d`, `rotateX`, `rotateZ`), ensuring smooth performance on both mobile and desktop.
*   **Autonomous Economy Engine:** A sophisticated simulation loop that calculates Treasury income, maintenance costs, population growth, and city beauty ratings every 5 seconds.
*   **Persistent State Management:** Integrated `localStorage` pipeline to ensure user progress is saved and recovered automatically across sessions.
*   **Dynamic Event System:** Includes randomized economic events (e.g., Recessions) that challenge the player's resource allocation strategy.
*   **Glassmorphism UI (HUD):** A modern, high-fidelity dashboard tracking XP progression, leveling logic, and real-time financial velocity.

---
Play CityOS Core Here ( npx plugins add vercel/vercel-plugin)

## 🛠️ Tech Stack & Architecture

*   **Frontend:** React 18 (Hooks, Memoization, Lifecycle Management)
*   **Styling:** CSS3 (Custom Properties, Flexbox, 3D Grid Matrix)
*   **Typography:** Plus Jakarta Sans
*   **Deployment:** Vercel / GitHub Pages

---

## 📦 Project Structure

Currently optimized into a semantic, production-ready single-file architecture for rapid deployment:
*   `index.html` — Contains the core React client, UI components, and the 3D simulation matrix.

---

## ⚙️ Local Setup Instructions

To run this project locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/cityos-core.git](https://github.com/YOUR_USERNAME/cityos-core.git)

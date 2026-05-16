<div align="center">
<img width="1376" height="768" alt="Mini Metro" src="https://github.com/user-attachments/assets/f1f73052-d096-4e3d-96e0-ad34408a93b4" />

# 🚇 Mini Metro

**Officially unofficial remake version — a minimalist subway strategy game for the browser.**

[![React](https://img.shields.io/badge/React-19.2.3-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8.2-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-6.2.0-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![License](https://img.shields.io/badge/License-Apache%202.0-D22128.svg)](https://opensource.org/licenses/Apache-2.0)

<p align="center">
  <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#how-to-play">How to Play</a> •
  <a href="#installation">Installation</a> •
  <a href="#roadmap">Roadmap</a>
</p>

<a href="https://lachiethurlow.com">Play at lachiethurlow.com</a>

</div>
  
---

## 📖 About

**Mini Metro** is a browser remake of the minimalist subway strategy game. Built with **TypeScript**, **React 19**, and **HTML5 Canvas**, it delivers 60fps pathfinding and rendering as you design efficient networks for a growing city.

By [Lachie Thurlow](https://lachiethurlow.com).

## Features
<img width="1514" height="888" alt="image" src="https://github.com/user-attachments/assets/813e0898-791d-41fb-ac0e-24905a2ba677" />

### Core gameplay
- **Draw-to-Connect Gameplay**: Intuitively create and modify metro lines.
- **Procedural City Growth**: Dynamic station spawning ensures every session presents a new logistical challenge.
- **Shape-Based Routing**: Passengers find their own way through your network based on their destination shape.
- **Weekly Upgrades**: Survive the week to choose between vital assets — new lines, locomotives, carriages, or tunnels.

### Game Modes
| Mode | Description |
| :--- | :--- |
| **Normal** | The classic experience. Balance efficiency and overcrowding. |
| **Extreme** | Once a line is placed, it's permanent. True strategic planning. |
| **Endless** | A zen-like sandbox mode. Build your dream network without the risk of game over. |

### Technical Highlights
- **60FPS Canvas Engine**: Optimized rendering loop for smooth train movement and UI interactions.
- **React 19 & TypeScript**: A modern codebase for complex simulations on the web.
- **Touch-First Design**: Fully responsive and playable on mobile devices with intuitive touch controls.

## How to Play

1.  **Connect Stations**: Click or touch and drag between geometric stations (Circle, Triangle, Square) to create a metro line.
2.  **Assign Trains**: Locomotives automatically run on your lines to transport passengers.
3.  **Optimize Routes**: Drag line ends to extend your network or rewire existing paths as the city expands.
4.  **Manage Overcrowding**: Keep an eye on the red indicators! If a station stays overcrowded for too long, the network fails.
5.  **Upgrade**: Every Sunday, choose a new asset to help your network keep up with the city's growth.

## Installation

Run locally:

```bash
# Clone the repository
git clone https://github.com/lachielocks/mini-metro.git

# Navigate to the project directory
cd mini-metro

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open `http://localhost:3000` in your browser to start building.

## Roadmap

- [ ] **City Presets**: Play on maps inspired by real-world cities like London and Paris.
- [ ] **Advanced Upgrades**: Interchange stations and multi-track support.
- [ ] **Soundscape**: Minimalist ambient audio.

## License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

---

<div align="center">

Made by [Lachie Thurlow](https://lachiethurlow.com)

</div>

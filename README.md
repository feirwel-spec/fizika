# 🔬 Physics Laboratory

An interactive web-based educational simulator for modeling and exploring physical phenomena using real-world mathematical equations. Built as a lightweight, standalone single-file application with zero external dependencies (pure HTML/CSS/JS).

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

---

## 🌟 Features

- **4 Core Physical Experiments:**
  - **Pendulum:** Mathematical pendulum simulation accounting for string length, initial angle, planetary gravity (Earth, Moon, Mars, Jupiter), and damping[cite: 1].
  - **Projectile Motion:** Ballistic trajectory analysis with adjustable launch velocity, angle, initial height, and air resistance toggle[cite: 1].
  - **Spring-Mass System:** Harmonic oscillations demonstrating kinetic/potential energy transformations and frictional energy dissipation[cite: 1].
  - **Ohm's Law:** Interactive DC circuits (series and parallel) with visual electron current flow and thermal resistor heating based on dissipated power[cite: 1].
- **Sandbox Mode (Free Setup):** A fully customizable playground where users can drag-and-drop objects (pucks, balls, weights, clay), surfaces (ice, trampolines, rough platforms), constraints (springs, ropes), and measuring instruments[cite: 1].
- **Real-time Data Visualization:** Dynamic canvas-based plotting of parameters (velocities, trajectories, energy charts) synchronized with numerical readouts[cite: 1].
- **Measurement Instruments:** Interactive tools including rulers, motion sensors, dynamometers, and stopwatches[cite: 1].
- **Experiment Logbook:** Save and review measurement parameters and outcomes on the fly[cite: 1].
- **Adaptive UI & Themes:** Responsive layout optimized for desktops and mobile touchscreens, featuring automatic Light/Dark mode support[cite: 1].

---

## ⚙️ Physics Engine & Tech Stack

- **Numerical Integration:** Motion and dynamics are computed numerically using the 4th-order Runge-Kutta (RK4) method with a fixed internal time-step ($\le 4\text{ ms}$) to ensure stability and precision[cite: 1].
- **State Persistence:** Sandbox setups and user configurations are automatically saved via browser `localStorage`[cite: 1].
- **Tech Stack:** Vanilla JavaScript (ES6+), HTML5 Canvas API, CSS3 (Variables, Grid, Flexbox), Google Fonts (Manrope, JetBrains Mono, Unbounded)[cite: 1].

---

## 🚀 Getting Started

No build tools, package managers, or servers are required to run the project.

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/your-username/physics-laboratory.git](https://github.com/your-username/physics-laboratory.git)

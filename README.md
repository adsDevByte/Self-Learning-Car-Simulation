# 🚗 Self-Learning Car Simulation

A simulation of a self-driving car that learns to navigate its environment using machine learning techniques. This project demonstrates how an autonomous agent can improve its driving behavior over time without explicit programming.

---

## 📌 Features

- 🧠 Self-learning AI car (no hardcoded driving logic)
- 🛣️ Dynamic road and environment simulation
- 👁️ Sensor-based perception (ray casting / distance detection)
- 📈 Real-time learning and improvement
- 🎮 Visualization of multiple cars (best model survives)
- ⚡ Lightweight and runs in the browser

---

## 🛠️ Tech Stack

- **JavaScript (Vanilla JS)**
- **HTML5 Canvas**
- Basic **Neural Network implementation**
- Optional: LocalStorage for saving the best model

---

## 📂 Project Structure

```bash
Self-Learning-Car-Simulation/
├── README.md        # Project documentation
├── index.html       # Entry point of the application
├── style.css        # Styling for UI
├── main.js          # Main simulation logic
├── car.js           # Car behavior and movement
├── controls.js      # User/control logic
├── road.js          # Road generation
├── sensor.js        # Sensor logic for detection
├── network.js       # Neural network implementation
├── utils.js         # Helper functions
└── visualizer.js    # Visualization of neural network

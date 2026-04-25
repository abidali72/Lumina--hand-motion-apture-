# Lumina 🌌

**Lumina** is a futuristic, browser-based hand-motion capture and interaction experiment. It uses computer vision to track your hands in real-time, surrounding them with vibrant neon particles and allowing you to "paint" in the air using simple gestures.

![Lumina Preview](https://raw.githubusercontent.com/abidali72/Lumina--hand-motion-apture-/main/preview.png) *(Note: Placeholder for preview image)*

## ✨ Features

- **Real-time Hand Tracking**: Powered by MediaPipe for high-precision, low-latency tracking.
- **Neon Particle Physics**: Dynamic, physics-based particles follow your hand movements with realistic damping and stiffness.
- **Pinch-to-Write**: A "Touchless Ink" system that lets you draw permanent neon lines by pinching your thumb and index finger.
- **Energy Bridges**: When two hands are detected, an energetic "Cat's Cradle" bridge forms between them, reacting to the distance and speed of your movements.
- **Responsive Design**: Automatically adjusts to your window size while preserving your drawings.
- **Minimalist UI**: An elegant, auto-fading interface that focuses on the experience.

## 🛠️ Technology Stack

- **Frontend**: HTML5, Vanilla CSS3, Javascript (ES6+)
- **Computer Vision**: [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- **Rendering**: Canvas 2D API with advanced composition modes (`lighter`, `screen`).
- **Hardware**: Uses standard webcams for motion capture.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Edge, or Brave recommended for best performance).
- A webcam.

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/abidali72/Lumina--hand-motion-apture-.git
   ```
2. Open `index.html` in your browser.
3. Allow camera permissions when prompted.
4. **Interaction**:
   - **Move hands**: Watch the neon particles follow your fingers.
   - **Pinch (Thumb + Index)**: Start drawing in the air.
   - **Two Hands**: Connect them to form energy strings.
   - **Clear Ink**: Use the button in the top-left to wipe the canvas.

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

---
Developed with ❤️ by [abidali72](https://github.com/abidali72)

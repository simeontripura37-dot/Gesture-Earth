 # 🌍 3D Earth Hand-Gesture Control

An interactive web application that loads a 3D Earth model (`earth.glb`) and allows you to rotate and zoom using hand gestures via your webcam—no touch screen or mouse needed.

Built using **Three.js** for 3D rendering and **Google MediaPipe Hands** for real-time AI computer vision.

---

## ✨ Features

- 🌐 **360° Rotation:** Move your hand left/right to spin the Earth on its Y-axis.
- 📐 **Vertical Tilt:** Move your hand up/down to tilt the Earth on its X-axis.
- 🔍 **Pinch Zoom:** Pinch your thumb and index finger together or apart to zoom in and out.
- 📱 **Cross-Platform:** Works on mobile devices (via browser/APK) and desktop PCs.
- 🚫 **No Touch Controls:** Completely hands-free control interface.

---

## 🛠️ Project Structure

```text
├── index.html     # Single-page web application with Three.js & MediaPipe
├── earth.glb      # 3D Earth model
└── README.md      # Project documentation

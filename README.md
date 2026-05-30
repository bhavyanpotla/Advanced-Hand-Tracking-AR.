# 🌟 NEON AURA AR — Advanced Hand Tracking Experience

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Flask](https://img.shields.io/badge/Framework-Flask-000000.svg?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![MediaPipe](https://img.shields.io/badge/AI-MediaPipe--Hands-0078D4.svg)](https://ai.google.dev/edge/mediapipe/solutions/guide)

An immersive, web-based Augmented Reality (AR) application that leverages computer vision to track hand gestures, render glow-in-the-dark interactive visual engines, and generate dynamic ambient synthesizer soundscapes in real-time.

---

## 📸 Preview Image Through Drive

*When running successfully, your browser interface will look like this:*

[https://drive.google.com/file/d/1lhipq411kTARiTQEGPNQ7IiHMfrV70CL/view?usp=sharing](url)

---

## ✨ Features

### 🧠 1. Real-Time Computer Vision
* Powered by Google's **MediaPipe Hands** engine to accurately detect 21 skeletal coordinates per hand.
* Cross-hand geometric interaction tracking (Mandala geometry and electricity arcs when tracking 2 hands simultaneously).

### 🎨 2. Visual Effects & Physics Engine
* **Neon Glow Rendering:** Utilizes HTML5 Canvas `screen` blending mode for bright, overlapping neon lights.
* **Fingertip Particle Fountains:** Generates colorful gravity-based sparks based on fingertip coordinates.
* **Matrix Rain Background:** Background starfield drop rates dynamically adapt and speed up according to hand velocity.
* **5 Dynamic Color Themes:** Interactive UI control panel to switch color pallets instantly:
  * 🌈 Rainbow
  * 🌐 Cyberpunk
  * 🌋 Lava
  * 🌊 Ocean
  * 🌌 Galaxy

### 🎵 3. Web Audio Synthesis Engine
* **Synthesized Theremin-like Hum:** Modulates audio pitch and volume continuously depending on the physical proximity of your two indexing fingers.
* **Haptic Audio Zapping:** Triggered interactively via pinch gestures.

### 📊 4. Integrated Heads-Up Display (HUD)
* Beautifully designed frosted glass micro-frontend overlay showing live **FPS indicators**, **Active Hand Count**, **Gesture Recognition Status** (*Open Hand vs. Fist*), and **Finger Spread Percentages**.

---

## 🛠️ Tech Stack & Dependencies

* **Backend Routing:** Python 3.x, Flask
* **Frontend Design:** HTML5, CSS3 Custom Properties (Glassmorphism architecture)
* **Graphics Rendering:** Vanilla HTML5 Canvas (Dual-layer layout: `#bgCanvas` + `#mainCanvas`)
* **AI Framework:** `@mediapipe/hands`, `@mediapipe/camera_utils`

---

## 🚀 Quick Start & Installation

Follow these steps to run the application locally on your computer:

### Step 1: Clone the Repository
```bash
git clone https://github.com/bhavyan_potla/Advanced-Hand-Tracking-AR.git
cd Advanced-Hand-Tracking-AR
```

### Step 2: Install Python Dependencies
Ensure you have Python installed, then set up Flask:
```bash
pip install flask
```

### Step 3: Project Directory Layout
Verify your local project folder matches this architecture layout:
```plaintext
├── app.py                  # Flask Application Server
└── templates/
    └── index.html          # Web Interface UI & MediaPipe JS Logic
```

### Step 4: Launch the Server
Execute the Flask server by running:
```bash
python app.py
```

### Step 5: Open your Web Browser
Navigate to the running web page address:
```plaintext
http://127.0.0.1:8000
```

> **Note:** Click the *"Enter Experience"* button upon page load to grant webcam permissions and let the browser initiate the AudioContext loop safely.

---

## 🎮 How to Control the Experience

- **Fist vs Open Hand:** Watch the HUD detect gestures as you expand or draw in your fingers.
- **Pinch Gesture (Thumb + Index Finger):** Triggers a neon color shockwave ring along with a high-voltage audio zap sound effect.
- **Two Hands Proximity:** Bring your index fingers closer together to elevate the volume and pitch of the synthesizer system hum.
- **Speed Shifting:** Move your hands quickly through the frame to hyper-accelerate the background particle rain.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for configuration details.

---

## 🏷️ Hashtags

#HandTracking #AugmentedReality #AR #ComputerVision #MediaPipe #Flask #JavaScript #HTML5Canvas #WebAudio #NeonGlow #GenerativeArt #InteractiveDesign #OpenSource #MITLicense #WebAR #GestureRecognition #RealTimeVisualization #Theremin #ParticleEffects #Glassmorphism

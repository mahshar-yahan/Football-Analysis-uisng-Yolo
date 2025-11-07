# ⚽ Football Player Tracking and Analysis

## 🧠 Overview
This project detects and tracks **players, referees, and footballs** in a video using **YOLO**. It also classifies players into teams using **KMeans** based on t-shirt color, analyzes **ball possession**, and measures **speed and distance** covered by each player using **Optical Flow** and **Perspective Transformation**.

## 🚀 Features
- 🎯 Player, referee, and ball detection (YOLO)
- 👕 Team assignment using KMeans clustering
- 🔄 Camera motion handling with Optical Flow
- 🌍 Perspective transformation for real-world distance
- 🏃 Speed and distance calculation per player
- 📊 Ball possession analysis

## 🧩 Modules
| Module | Purpose |
|---------|----------|
| **YOLO** | Object detection |
| **KMeans** | Team color clustering |
| **Optical Flow** | Camera movement estimation |
| **Perspective Transformation** | Convert pixels to meters |
| **Speed & Distance Calculation** | Player performance metrics |

## ⚙️ Setup
```bash
git clone https://github.com/yourusername/football-tracking-yolo.git
cd football-tracking-yolo
pip install -r requirements.txt

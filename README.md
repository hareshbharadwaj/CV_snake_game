# CV_snake_game
Playing a snake game with only using your hands to control the direction

# 🐍 Hand-Controlled Snake Game

This is a Python-based Snake Game that uses your **hand gestures** to control the snake using your **webcam**. The game uses **MediaPipe** for real-time hand tracking and **OpenCV** for game rendering.

---

## 🎮 Features

- Control snake using palm movement (up, down, left, right)
- Game pauses when hand leaves control zone
- Resume with a countdown when hand is back
- Different food types with varying points and sizes
- Win the game at a score of 100
- Visual joystick on screen to guide hand movements

---

## 🧠 Technologies Used

- `Python 3.x`
- `OpenCV`
- `MediaPipe`
- `NumPy`
- Real-time webcam input for interaction

---

## 📦 Requirements

Install dependencies via pip:

```bash
pip install opencv-python mediapipe numpy

✋ Controls
Palm inside circle → Snake moves in the direction of palm tilt

Palm out of circle → Game pauses

Open hand (≥ 3 fingers) → Resume game

Press R → Restart game

Press ESC → Exit game

📷 Visual Guide
A circle on the screen represents the control zone.

Arrows inside the circle show movement directions.

Hand landmarks are drawn to visualize tracking.

🏆 Objective
Reach a score of 100 by eating food items:

🟢 Small (2 points)

🟠 Medium (5 points)

🔴 Large (10 points)

⚠️ Notes
Ensure good lighting for accurate hand detection.

Performance may vary depending on webcam quality and processing power.

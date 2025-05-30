# aarti

# ✋ Hand Gesture Controller

Control your keyboard using hand gestures captured from your webcam using AI-powered hand tracking.  
This Python project uses **Mediapipe**, **OpenCV**, and **PyAutoGUI** to map finger gestures into directional keyboard commands (up, down, left, right).

---

## 🧠 Features

- 🤖 Real-time hand tracking with Mediapipe
- ✌️ Finger gesture detection (Thumb, Index, Middle, etc.)
- ⌨️ Keyboard control with gestures:
  - 4+ fingers: Jump (↑)
  - 0 fingers: Slide (↓)
  - 1 finger (left side): Move Left (←)
  - 1 finger (right side): Move Right (→)
- 🔄 Cooldown system to avoid repeated triggers
- 👀 Live gesture feedback on screen

---

## 🛠 Tech Stack

- Python
- OpenCV
- Mediapipe
- PyAutoGUI

---

## 🚀 How to Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/aartisonigra/hand-gesture-controller.git
   cd hand-gesture-controller


2.Install dependencies:

pip install opencv-python mediapipe pyautogui


3.Run the script:

python app.py

📁 Project Structure

hand-gesture-controller/
├── hand_gesture_control.py   # Main Python script
├── README.md                 # This file
└── .gitignore                # Git ignored files



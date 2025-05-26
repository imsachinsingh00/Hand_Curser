# Hand Cursor Controller

This project allows controlling the mouse pointer using hand gestures captured via a webcam.

## 📁 Project Structure

- `main.py`: Main script for capturing video and recognizing hand gestures.
- `README.md`: Documentation.

## ✋ Description

Using the MediaPipe framework, the project detects hand landmarks and translates gestures into mouse movements with `pyautogui`.

## ⚙️ Requirements

- Python 3.x
- OpenCV
- MediaPipe
- pyautogui

Install with:
```bash
pip install opencv-python mediapipe pyautogui
```

## 🚀 How to Run

1. Make sure your webcam is connected.
2. Run the script:
```bash
python main.py
```
3. Move your hand in front of the camera. The cursor will follow.

## 🧠 Features

- Index finger tracking
- Finger tip landmark detection
- Gesture-based control

## 📄 License

MIT License.

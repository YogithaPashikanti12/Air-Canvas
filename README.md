# Air-Canvas
# 🖐️ Air Canvas(Virtual Hand Paint) using OpenCV & MediaPipe
This project is a hand-tracking based virtual paint application using Python, OpenCV, and MediaPipe. It lets you draw on a virtual canvas using finger gestures captured by your webcam — no physical touch required!

## ✨ Features
- Real-time hand and finger tracking using MediaPipe
- Use index finger as a virtual paintbrush
- Switch colors (Blue, Green, Red, Yellow) with gestures
- Clear canvas using a virtual button
- Draw on both the live feed and a persistent canvas

## How it works
Clone the repository and run the script:
python air_canvas.py

## Controls:
Use Index Finger: Start drawing.
Touch Thumb & Index Finger: Lift the brush (stop drawing).
Raise Finger to Buttons Area (Top):
    Click on color boxes to switch brush color
    Click on "CLEAR" to reset the canvas
Press 'q': Quit the application

## How it Works
Uses MediaPipe Hands to detect hand landmarks
Tracks index finger position to determine brush position
Detects color switch and clear commands when the finger hovers over UI buttons
Draws strokes in real-time using OpenCV line function

## 🛠️ Requirements 
Install the following Python packages:
python 3.10.0
```bash
py -3.10 -m pip install mediapipe opencv-python numpy





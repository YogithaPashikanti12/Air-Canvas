# Air-Canvas
# 🖐️ Air Canvas(Virtual Hand Paint) using OpenCV & MediaPipe
This project is a hand-tracking based virtual paint application using Python, OpenCV, and MediaPipe. It lets you draw on a virtual canvas using finger gestures captured by your webcam — no physical touch required!

## ✨ Features
- Real-time hand and finger tracking using MediaPipe
<br>- Use index finger as a virtual paintbrush
<br>- Switch colors (Blue, Green, Red, Yellow) with gestures
<br>- Clear canvas using a virtual button
<br>- Draw on both the live feed and a persistent canvas

## How it works
Clone the repository and run the script:
python air_canvas.py

## Controls:
Use Index Finger: Start drawing.
<br>Touch Thumb & Index Finger: Lift the brush (stop drawing).
<br>Raise Finger to Buttons Area (Top):
    <br>Click on color boxes to switch brush color
    <br>Click on "CLEAR" to reset the canvas
<br>Press 'q': Quit the application

## How it Works
Uses MediaPipe Hands to detect hand landmarks
<br>Tracks index finger position to determine brush position
<br>Detects color switch and clear commands when the finger hovers over UI buttons
<br>Draws strokes in real-time using OpenCV line function

## 🛠️ Requirements 
<b>python 3.10.0 </b>
<br>
Install the following Python packages:

```bash
py -3.10 -m pip install mediapipe opencv-python numpy





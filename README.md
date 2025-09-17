# AirCanvas - Draw in the Air with Hand Gestures

AirCanvas is a Python project that lets you **draw in the air using your hand**. It uses **OpenCV**, **Mediapipe**, and **NumPy** to track your hand and render drawings in real time.

## Features

- Draw using your **index finger** tracked via your webcam.
- Real-time rendering on screen.
- Supports multiple pen colors (can be extended).
- Clear the canvas when needed.

## Requirements

- Python 3.10 (Mediapipe currently supports up to 3.10)
- OpenCV
- Mediapipe
- NumPy

## Installation

1. Clone this repository:

```bash
git clone https://github.com/Afrin2627/AirCanvasProject.git
cd AirCanvasProject


2. Create a virtual environment (optional but recommended):

python -m venv venv

3. Activate the virtual environment:

Windows (cmd.exe):

venv\Scripts\activate.bat
PowerShell:

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
venv\Scripts\activate.ps1

4. Install dependencies:

pip install -r requirements.txt

Usage

Run the main Python file:

python air_canvas.py


Your webcam will open.

Move your index finger to draw on the screen.

Press Q to quit.

Notes

Ensure your background is well-lit for better hand tracking.

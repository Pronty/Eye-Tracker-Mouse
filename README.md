# Eye-Controlled Mouse

## Overview

This project implements an eye-tracking-based mouse control system using Python. By leveraging computer vision techniques and the Mediapipe library, this script allows users to control the mouse cursor with their eyes. It tracks facial landmarks and detects eye movements, enabling cursor control and clicks based on the position of the eyes.

## Features

- **Real-Time Eye Tracking**: Utilizes Mediapipe’s Face Mesh solution to track facial landmarks and detect eye movements in real-time.
- **Cursor Control**: Maps eye movements to screen coordinates, allowing users to move the cursor by moving their eyes.
- **Click Detection**: Detects when the user blinks and triggers a mouse click using the PyAutoGUI library.

## Technologies Used

- **Python**: The programming language used to develop the application.
- **OpenCV**: For video capture and image processing.
- **Mediapipe**: For facial landmark detection and eye tracking.
- **PyAutoGUI**: For simulating mouse movements and clicks.

## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- PyAutoGUI


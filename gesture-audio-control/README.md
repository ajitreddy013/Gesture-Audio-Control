# Gesture-Based Audio Control

This project implements a gesture-based audio control system using OpenCV and MediaPipe. It allows users to adjust the system volume by moving their thumb and index finger closer or further apart.

## Overview

The Gesture-Based Audio Control application captures video from the user's webcam and processes hand landmarks to detect the distance between the thumb and index finger. The distance is then mapped to a volume level, which is adjusted in real-time.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/gesture-audio-control.git
   cd gesture-audio-control
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   python src/main.py
   ```

2. Position your hand in front of the webcam, ensuring that your thumb and index finger are visible.

3. Move your thumb and index finger closer together to decrease the volume and further apart to increase the volume.

4. Press 'q' to exit the application.

## Dependencies

- OpenCV
- MediaPipe
- NumPy

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
# Hand Gesture Volume Control using OpenCV and MediaPipe

This project implements a hand gesture-based volume control system using OpenCV, MediaPipe, and pycaw libraries. 
It allows users to control the system's audio volume by making specific hand gestures in front of the camera.

## Features

- Detects and tracks hand landmarks using the MediaPipe library.
- Calculates the distance between specific hand landmarks to determine the desired volume level.
- Changes the system's audio volume based on the hand gesture.
- Provides visual feedback on the screen about the detected hand and volume level.

## Requirements

- Python 3.x
- OpenCV
- Mediapipe
- Numpy
- pycaw

## Getting Started

1. Clone the repository:

https://github.com/akshaylenkala/Gesture-Control-Volume-system
cd hand-gesture-volume-control


2. Install the required libraries:

pip install opencv-python mediapipe numpy pycaw


3. Run the main script:

python main.py


4. Position your hand in front of the camera, and perform specific hand gestures to control the volume.

## Usage

- Place your hand in the camera frame to detect and track your hand.
- Keep your palm open and raise your thumb to increase the volume.
- Close your fist to decrease the volume.
- Show your open palm with all five fingers extended to set the volume to the detected level.

## Troubleshooting

If you encounter any issues or have questions, please feel free to create an issue in this repository.

## Acknowledgments

- The hand tracking functionality is based on the Mediapipe library developed by Google.
- The pycaw library is used to interact with the Windows Core Audio API for volume control.
- Special thanks to the OpenCV community for their contributions.

# Hand Gesture Finger Counter

A real-time finger counting system using **OpenCV**, **background subtraction**, and **convex hull geometry**.

## Features

- Webcam-based hand detection
- Background modeling and segmentation
- Finger counting via convex hull analysis

## Requirements

- Python 3.x
- OpenCV
- NumPy
- scikit-learn

pip install opencv-python numpy scikit-learn

## Usage

1. Run the script
2. Keep the ROI empty for the first 60 frames (background calibration)
3. Place your hand inside the red box
4. Finger count is displayed in real time

Press **ESC** to exit.

## Notes

- Works best with stable lighting and background
- ROI and threshold values may need tuning

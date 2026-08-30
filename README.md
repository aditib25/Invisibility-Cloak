# 🪄 Invisibility-Cloak
A real-time computer vision project that creates an invisibility cloak effect using OpenCV and HSV color segmentation, demonstrated with a blue cloth.

## Project Overview

The program:

- Captures the background using the webcam before the user enters the frame.
- Captures live webcam frames and processes them continuously.
- Converts each frame from BGR to HSV, making color-based segmentation easier.
- Detects the blue cloth using HSV color thresholding.
- Creates a binary mask where the detected blue region is separated from the rest of the frame.
- Cleans the mask using morphological operations to reduce noise and improve the detected region.
- Replaces the detected blue region with the previously captured background.
- Combines the background and live frame to create the invisibility effect.
- Displays the processed video in real time through Jupyter Notebook.
- Optionally saves the processed output as an MP4 video file.

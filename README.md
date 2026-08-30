# Invisibility-Cloak
A real-time computer vision project that creates an invisibility cloak effect using OpenCV and HSV color segmentation, demonstrated with a blue cloth.

## Project Overview

The program:
- Captures the background before the user enters the frame.
- Detects a blue-colored cloth using HSV color segmentation.
- Creates a binary mask for the blue cloth.
- Replaces the detected blue region with the previously captured background.
- Displays the result in real time.
- Optionally saves the processed video as an MP4 file.

## How the project works:

1. Capture the background
2. Capture live webcam frames
3. Convert the frame from BGR to HSV
4. Detect the blue cloth using HSV thresholding
5. Create and clean the mask
6. Replace the blue region with the saved background
7. Combine the background and current frame
8. Display the final result

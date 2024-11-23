# Video Processing with OpenCV

This project demonstrates video frame processing using OpenCV. The script processes a video file (`visc.MOV`) to isolate and manipulate specific color channels, apply Gaussian blur, threshold the image, and detect edges.

## Features

- **Channel Mixing:** Combines RGB channels using custom weights to create an isolated representation.
- **Gaussian Blur:** Smooths the processed image to reduce noise.
- **Thresholding:** Binarizes the blurred image based on intensity.
- **Edge Detection:** Identifies edges using the Canny Edge Detection algorithm.

## Requirements

Ensure the following dependencies are installed:
- Python 3.x
- OpenCV (`cv2`)
- NumPy

Install dependencies via pip:
```bash
pip install opencv-python numpy

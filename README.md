# Video Processing with OpenCV

This project demonstrates video frame processing using OpenCV. The script processes a video file (`visc.MOV`) to isolate and manipulate specific color channels, apply Gaussian blur, threshold the image, and detect edges.
![Real time edge detection](https://github.com/user-attachments/assets/5ec9d6b7-c432-4022-b705-7f3a2b227478)

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

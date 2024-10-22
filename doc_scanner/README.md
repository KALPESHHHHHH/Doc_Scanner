# Document Scanner

This project implements a document scanning pipeline using OpenCV and Python, capable of detecting the edges of a document, extracting contours, and projecting the best contour to create a flat, noise-free document view. This project follows five key steps:

## Steps
1. **Removing the Noise**: Using various image processing techniques to remove noise and make the document boundaries clearer.
2. **Edge Detection**: Detecting the edges of the document using methods like Canny edge detection.
3. **Contour Extraction**: Finding the contours of the detected document from the edge-detected image.
4. **Best Contour Selection**: Choosing the best contour that represents the document outline by filtering based on contour size and shape.
5. **Project to the Screen**: Warping the perspective of the document so that it appears flat and correcting any distortion.

## Features
- Noise reduction to improve contour detection.
- Accurate edge detection using OpenCV’s Canny algorithm.
- Contour extraction and filtering to ensure the correct document is selected.
- Perspective transformation to create a flat, undistorted view of the document.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/document-scanner.git
   cd document-scanner

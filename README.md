# Overview

This project aims to detect and highlight lane lines in a video, providing a visual representation of vehicle lanes using computer vision techniques.

## Features

- **Canny Edge Detection:** Converts the video frames to grayscale, applies Gaussian blur, and then utilizes the Canny edge detection algorithm to identify edges in the image.

- **Region of Interest Masking:** Focuses on the region of the image where lane lines are expected, masking out irrelevant areas.

- **Hough Transform:** Utilizes the Hough transform to identify lines in the region of interest.

- **Average Slope Intercept:** Averages the slope and intercept of detected lines to form a single representative line for the left and right lanes.

- **Visualization:** Draws the detected lane lines on the original video frames, creating an output video with highlighted lanes.

## Dependencies

- **OpenCV:** Open Source Computer Vision Library.
- **NumPy:** Fundamental package for scientific computing with Python.
- **Matplotlib:** Python plotting library.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/your-lane-detection-repo.git

🖼 Image Processing with OpenCV

A small project showcasing image manipulation, color space transformations, geometric operations, and object detection using Python and OpenCV.

🚀 Features

Task 1: Combine multiple color channels (RGB, HSV, Lab) into one image.

Task 2: Perform flips, rotations, and random region zeroing.

Task 3: Detect and count blue "X" shapes in an image.

📦 Requirements

Python 3.7+

Libraries: opencv-python, numpy, matplotlib

Install with:

pip install opencv-python numpy matplotlib
🖌 Tasks
Task 1 – Color Channel Visualization

Resize original image to 50%.

Display:

Top Left: Original

Top Right: V channel of HSV (Red tones)

Bottom Left: L channel of Lab (Green tones)

Bottom Right: B channel of RGB (Blue tones)

Example output:

Task 2 – Image Transformations

Horizontal Flip

Rotate 90° clockwise

Rotate 45°

Random 100x100 zeroed region

Example output:

Task 3 – Blue X Detection

Detect and count blue "X" shapes in red_x.png.

Steps:

Convert image to HSV

Mask for blue color

Morphological cleaning

Contour detection & area filtering

Draw contours & count Xs

Example output (Blue X count: 26):

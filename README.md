# omr-Reader
A Python-based Optical Mark Recognition (OMR) tool designed to evaluate exam sheets efficiently. This tool leverages OpenCV and Streamlit to detect, preprocess, and evaluate OMR sheets, providing an accurate and user-friendly solution for educational and professional use.

# Features

Automatic Rotation Detection: Corrects skewed or rotated OMR sheets using Hough Line Transform.

Preprocessing and Noise Reduction: Ensures accurate evaluation by applying Gaussian blur and adaptive thresholding.

Contour Detection: Identifies and extracts the sheet area using perspective transformation.

Bubble Detection: Accurately identifies marked answers using contour analysis.

Customizable Answer Key: Users can define the correct answers through a simple sidebar interface.

Score Calculation: Computes the score and overlays it on the processed sheet image

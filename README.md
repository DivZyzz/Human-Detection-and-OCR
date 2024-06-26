# Human Detection with Text Extraction

## Overview
This project utilizes computer vision techniques to detect humans in images and videos, employing the Histogram of Oriented Gradients (HOG) descriptor. Additionally, it extracts text from frames using Tesseract OCR. The integration of visual object detection and text extraction demonstrates the potential of combining computer vision with natural language processing.

## Features
- Detects humans in images and videos using HOG descriptor.
- Extracts text from frames using Tesseract OCR.
- Displays detected humans and extracted text on the frames.
- Supports image, video, and webcam input.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- Pytesseract
- imutils

## Usage
1. Install the required dependencies using pip:
pip install opencv-python numpy pytesseract imutils


2. Run the `human_detection.py` script with appropriate command-line arguments:

python human_detection.py -i <path_to_image> # For image input
![image](https://github.com/DivZyzz/Human-Detection-and-OCR/assets/136096930/66f4a2a3-988a-4786-b465-12e1ad74098d)

python human_detection.py -v <path_to_video> # For video input
![image](https://github.com/DivZyzz/Human-Detection-and-OCR/assets/136096930/51d59bcf-3fe6-481d-9af2-0678585fa955)

python human_detection.py -c true # For webcam input


## Notes
- Ensure Tesseract OCR is installed and configured on your system for text extraction.
- Adjust detection parameters in the code as needed for optimal performance.

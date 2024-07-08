# Text Detection and Recognition Application

## Overview
This Text Detection App uses Python libraries such as Tesseract, OpenCV, and Pillow to extract and process text from images. The app can handle simple text extraction as well as more complex image processing tasks to improve text detection accuracy. Additionally, a Flask web application is included to provide a user-friendly interface for the text detection functionality.              

## Features     
- Extract text from an image using Tesseract OCR.
- Remove irrelevant symbols from extracted text. 
- Perform various image preprocessing operations using OpenCV:
  - Grayscale conversion
  - Noise removal
  - Thresholding
  - Erosion  
  - Morphology operations
  - Canny edge detection
  - Skew correction  
  - Template matching
- Draw rectangles around detected text.
- Highlight specific words or patterns in the image.

## Requirements
- Python 3.x
- Requests
- Pillow
- pytesseract
- OpenCV
- numpy
- re
- Flask

## Installation
1. Install Tesseract OCR from [here](https://github.com/tesseract-ocr/tesseract). Ensure that Tesseract is added to your system path.
2. Install the required Python packages:
    ```bash
    pip install requests
    pip install pillow
    pip install pytesseract
    pip install opencv-python
    pip install numpy
    pip install flask
    ```

## Usage
1. Ensure Tesseract is correctly installed and its path is configured in the script.
2. Navigate to the folder containing the app:
    ```bash
    cd Text Extraction Flask App
    ```
3. Run the Flask application:
    ```bash
    python app.py
    ```
4. Open a web browser and go to `http://127.0.0.1:5000/` to access the application.

# Text_Detection_and_Recognition
                                                                            
                     
This Python script demonstrates text detection and recognition using a combination of Optical Character Recognition (OCR) and OpenCV techniques. It is a versatile tool for extracting text from images, which can be useful for various applications such as digitizing scanned documents or processing images containing complex text.

## Features
        
- Imports necessary libraries for OCR and image processing.
- Uses Tesseract OCR with custom configurations to extract text from an image.                       
- Performs image processing tasks with OpenCV, including grayscale conversion, noise removal, thresholding, erosion, Canny edge detection, deskew correction, and template matching.
- Draws rectangles around detected text regions.
- Highlights specific patterns or words based on predefined patterns.

## Usage
                                                       
1. Install the required libraries (Tesseract, OpenCV, and other dependencies).

2. Configure Tesseract OCR by setting the executable path.                                   

3. Load an image, either from a URL or a local file.

4. Run the script to extract and process text from the image.

5. Adjust configurations and patterns for your specific use case.

## Example

You can see the code in action by running it and exploring the results in the provided example image ('sample.png').

```bash
python text_detection_recognition.py

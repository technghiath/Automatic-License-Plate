# Automatic-License-Plate

Automatic License Plate Recognition (ALPR) is a technology that uses optical character recognition (OCR) to automatically read license plate characters. 

ALPR involves three major steps:
# Note for windown:
Refer install tesseract-ocr: https://tesseract-ocr.github.io/tessdoc/Installation.html
1.	License Plate Detection – This is the most important stage of the system. At this stage, the system determines the position of the license plate, inputs an image of the vehicle, and outputs the license plate.

2.	Character Segmentation – This stage is where the characters on the license plate get mapped out and segmented into individual images.

3.	Character Recognition – This stage is where the segmented characters are identified.

Here, the system uses Python, OpenCV and Tesseract to identify vehicles by their license plates and stored along with the date and time in a CSV file. OpenCV is used to detect number plates and Python Tesseract is used to extract characters and digits from the number plates. 

&nbsp;

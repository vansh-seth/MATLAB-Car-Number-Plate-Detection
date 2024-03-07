# MATLAB-Car-Number-Plate-Detection

Reference and code from here https://circuitdigest.com/tutorial/vehicle-number-plate-detection-using-matlab-and-image-processing


# Car Number Plate Detection Using MATLAB and Image Processing

## Overview

This project showcases an Automatic Number Plate Recognition (ANPR) system implemented using MATLAB and image processing techniques. The ANPR system captures images of vehicle license plates and processes them through various algorithms to extract alphanumeric information. This system finds applications in diverse settings such as petrol pumps, shopping malls, airports, highways, toll booths, hotels, hospitals, parking lots, and defense/military checkpoints.

If you're new to MATLAB or image processing, you can refer to our previous MATLAB projects:

- [Getting started with MATLAB: A Quick Introduction](#)
- [Getting Started with Image Processing using MATLAB](#)

## Key Components

The project consists of three main programs:

1. **Template Creation (template_creation.m):** This program is responsible for loading and saving binary images of alphanumeric characters into MATLAB memory.

2. **Letter Detection (Letter_detection.m):** This program reads characters from input images and identifies the highest matched corresponding alphanumeric character.

3. **Plate Detection (Plate_detection.m):** This program processes the input image and calls the above two files to detect the number plate.

## How to Use

### Template Creation

1. Create a folder for the project (e.g., Number Plate Detection) to store the files.
2. Save binary images of alphabets and numbers in a sub-folder named 'alpha'.
3. Open the MATLAB Editor window.
4. Copy and paste the code from `template_creation.m` into a new file named `template_creation.m` in the project folder.

### Letter Detection

1. Create a new file named `Letter_detection.m` in the project folder.
2. Copy and paste the code from `Letter_detection.m` into the new file.

### Plate Detection

1. Create a new file named `Plate_detection.m` in the project folder.
2. Copy and paste the code from `Plate_detection.m` into the new file.

## Execution

1. Run the `Plate_detection.m` file in MATLAB.
2. MATLAB will process the input image and display the detected number plate along with the alphanumeric characters extracted.

## Notes

- The project employs various image processing techniques such as grayscale conversion, binarization, edge detection, and region properties analysis.
- The `regionprops()` function is used to measure properties of image regions, such as bounding boxes and areas.
- Alphanumeric templates are stored and compared with input images to identify characters.

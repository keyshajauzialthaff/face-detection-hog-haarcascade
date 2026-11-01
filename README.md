# face-detection-hog-haarcascade

# Implementasi Face Detection Menggunakan Algoritma HOG dan Haarcascade

## Project Description

This project implements face detection using two algorithms: Haarcascade and Histogram of Oriented Gradients (HOG).

This project was developed as part of the Midterm Examination for the Unstructured Data Analysis course at Universitas Islam Bandung.

The experiment uses an image of lecturers from the Statistics Study Program as the test image.

## Objectives

1. Read and load an image using OpenCV.
2. Perform image preprocessing.
3. Resize the image to 800 × 600 pixels.
4. Convert the image into grayscale.
5. Detect faces using Haarcascade.
6. Detect faces using HOG.
7. Compare the detection results of both algorithms.

## Tools and Libraries

- Python
- Google Colab
- OpenCV
- Dlib
- Google Drive

## Methodology

### 1. Image Preprocessing

The original image is processed through the following steps:
- Read the image using OpenCV.
- Resize the image to 800 × 600 pixels.
- Convert the image into grayscale.

### 2. Face Detection

**A. Haarcascade**

Face detection is performed using OpenCV's CascadeClassifier with a scale factor of 1.25.

**B. Histogram of Oriented Gradients (HOG)**

Face detection is performed using Dlib's frontal face detector.

## Experimental Results

| Algorithm | Number of Faces Detected |
|---|---:|
| Haarcascade | 10 |
| HOG | 10 |

## Conclusion

Based on the experiment, both Haarcascade and HOG successfully detected 10 faces in the test image.

According to the analysis in the original report, HOG is considered more accurate than Haarcascade because it does not require explicit scale factor configuration, making its detection more stable and consistent across different object sizes and conditions.

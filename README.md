# AI Powered License Plate Detector

An AI-powered Automatic License Plate Recognition (ALPR) system designed to detect Indian vehicle license plates from images and recognize the alphanumeric characters using Computer Vision and Deep Learning.

---

## Overview

This project performs automatic license plate detection and character recognition through a multi-stage image processing and machine learning pipeline.

The system consists of:
- License Plate Detection
- Image Preprocessing
- Character Segmentation
- Character Recognition
- License Plate Text Generation

---

## Features

- Detects Indian vehicle license plates
- Automatic plate extraction from images
- Image enhancement and noise removal
- Character segmentation
- CNN-based character recognition
- Generates complete license plate number
- Modular and extensible pipeline

---

# System Workflow

```

Input Image
│
▼
Vehicle Image Acquisition
│
▼
License Plate Detection
(Haar Cascade)
│
▼
Plate Extraction
│
▼
Image Preprocessing
• Grayscale
• Thresholding
• Erosion
• Dilation
• Noise Removal
│
▼
Character Segmentation
│
▼
Character Recognition
(CNN Model)
│
▼
Character Prediction
│
▼
License Plate Generation
│
▼
Output Plate Number

```

---

# Project Pipeline

1. Capture or load vehicle image
2. Detect license plate region
3. Crop detected plate
4. Perform image preprocessing
5. Segment individual characters
6. Classify characters using CNN
7. Combine predicted characters
8. Display final license plate number

---

# Tech Stack

## Programming Language
- Python

## Computer Vision
- OpenCV

## Deep Learning
- TensorFlow
- Keras

## Machine Learning
- Scikit-Learn

## Numerical Computing
- NumPy

## Data Handling
- Pandas

## Development Environment
- Jupyter Notebook

---

# Image Processing Techniques

- Grayscale Conversion
- Binary Thresholding
- Morphological Erosion
- Morphological Dilation
- Contour Detection
- Character Segmentation
- Image Resizing
- Noise Removal

---

# Deep Learning Model

Model Type:

- Convolutional Neural Network (CNN)

Architecture:

- Conv2D
- MaxPooling2D
- Dropout
- Flatten
- Dense Layer
- Softmax Output Layer

Output Classes:

- 26 Alphabets (A-Z)
- 10 Digits (0-9)

Total Classes: **36**

---

# Project Structure

```

AI-License-Plate-Detector/
│
├── data/
│ ├── train/
│ └── validation/
│
├── models/
│
├── notebooks/
│
├── images/
│
├── indian_license_plate.xml
│
├── character_detection.py
├── plate_detection.py
├── train_model.py
├── predict.py
│
├── requirements.txt
└── README.md

```




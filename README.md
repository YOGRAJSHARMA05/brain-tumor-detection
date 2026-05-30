# Brain Tumor Detection using Image Processing and OpenCV

## Overview

This project is a Computer Vision and Medical Image Analysis system that detects potential brain tumors from MRI scans using image processing techniques. The system analyzes MRI images by applying preprocessing, thresholding, contour detection, and asymmetry analysis to identify suspicious tumor regions.

The project demonstrates how traditional image processing methods can be used for medical image analysis without requiring deep learning models or GPU resources.

---

## Features

- MRI image preprocessing
- Grayscale image conversion
- Gaussian noise reduction
- Adaptive thresholding
- Bright region segmentation
- Contour detection and analysis
- Brain hemisphere asymmetry analysis
- Tumor region highlighting
- Visual detection results

---

## Methodology

### Image Preprocessing
- Image resizing
- Grayscale conversion
- Gaussian blur filtering

### Region Detection
- Bright region extraction
- Binary mask generation
- Contour identification

### Tumor Analysis
- Detection of abnormal bright regions
- Brain asymmetry calculation
- Suspicious tumor region localization

### Decision Making
The system combines:
- Contour-based region detection
- Brightness analysis
- Brain asymmetry measurements

to determine whether a tumor may be present.

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

---

## Project Workflow

1. Load MRI image
2. Preprocess image
3. Apply thresholding
4. Detect contours
5. Analyze brain asymmetry
6. Identify suspicious regions
7. Display tumor detection results

---

## Advantages

- Fast execution
- Lightweight implementation
- No GPU required
- Easy to understand and modify
- Suitable for educational and research demonstrations

---

## Limitations

- Uses traditional image processing techniques
- Performance depends on MRI image quality
- Not intended for clinical diagnosis
- Requires further validation for medical applications

---

## Project Type

Computer Vision and Image Processing based Brain Tumor Detection System.

---

## Author

**Yograj Sharma**  
B.Tech Computer Science and Engineering  
SRM Institute of Science and Technology

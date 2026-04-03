# DIP-Image-Enhancement-System

**Smart Image Enhancement & Analysis System – Lab 06 Project**

---

## Overview

This project enhances low-quality images using image processing techniques from **Lab 01 to Lab 06**.  
The system takes an input image and produces a visually improved output along with analytical insights such as **brightness, contrast, and histogram analysis**.

---

## Features by Lab

### Lab 01 – Image Acquisition
- Load RGB or grayscale images  
- Convert RGB to grayscale  
- Display image resolution, data type, and a sample of the image matrix  

### Lab 02 – Sampling & Quantization
- Upsample and downsample images (0.25×, 0.5×, 1×, 1.5×, 2×)  
- Reduce bit depth (8-bit, 4-bit, 2-bit)  
- Compare visual quality and analyze degradation  

### Lab 03 – Geometric Transformations
- Rotate images (30°, 45°, 60°, 90°, 120°, 150°, 180°)  
- Apply translation and shearing  
- Attempt inverse transformations to restore original image  

### Lab 04 – Intensity Transformations
- Negative transformation  
- Logarithmic transformation  
- Gamma correction (γ = 0.5, 1.5)  
- Identify best method for brightening and highlighting details  

### Lab 05 – Histogram Processing
- Plot original histogram  
- Analyze contrast distribution  
- Apply histogram equalization  
- Compare before/after histograms  

### Lab 06 – Final Integrated Pipeline
- Grayscale conversion  
- Mild gamma correction  
- CLAHE (adaptive contrast enhancement)  
- Light sharpening for detail improvement  
- Output final enhanced image and compute brightness/contrast improvements  

---

## Folder Structure


DIP-Image-Enhancement-System/
│
├── main.py # Main script
│
├── images/
│ ├── input/ # Original input images
│ ├── output/ # Processed images (sampling, quantization, transformations, final enhancement)
│
├── README.md # This file
└── report.pdf # Lab report


---

## How to Run

1. Install required libraries:

```bash
pip install opencv-python matplotlib numpy
Place input images in the images/input/ folder.
Run the main script:
python code/main.py
Output images will be saved in the images/output/ folder.
Author
Name: Aadia Bibi
Registration ID: 235152
Instructor: Mr. Ghulam Ali
Name: [Your Name]

# Image-Edge-Detection-Contour-Extraction-Tool
Computer Vision Basics

Built a CV tool demonstrating pixel-level operations.

Shows understanding of grayscale conversion, thresholding, edge detection, and contour extraction.

Outputs are visual and easy to explain.

Can be run easily on Colab with uploaded images.


## Overview
A computer vision tool using OpenCV to demonstrate basic CV operations on images:
- Grayscale conversion
- Thresholding
- Edge detection (Canny)
- Contour extraction and drawing

## Features
- Upload your own images or use the sample images
- Outputs visual results for edges and contours
- Saves processed images to `assets/` folder

## Installation
```bash
pip install opencv-python matplotlib
```

GitHub Folder Structure

```
cv-basics-tool/
│── edge_detection_colab.ipynb      ← Colab notebook
│── sample_images/                  ← Folder with sample images
│    ├── image1.jpg
│    ├── image2.jpg
│── assets/                         ← To save output images if needed
│    ├── edges_image1.png
│    ├── contours_image1.png
│── README.md

```

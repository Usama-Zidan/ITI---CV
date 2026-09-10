# ITI Computer Vision Training (`ITI---CV`)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)](https://opencv.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](#)

This repository contains all lecture code, lab exercises, assignment tasks, and interactive projects completed during the **150-Hour Computer Vision Training Program** at the **Information Technology Institute (ITI)**.

---

## 📌 Training Summary & Highlights

* **Duration:** 150 Intensive Hours
* **Institution:** Information Technology Institute (ITI)
* **Domain:** Computer Vision, Image Processing & Deep Learning / Object Detection
* **Key Focus Areas:**
  - **Image Processing Foundations:** Spatial filtering, transformation, histograms, thresholding, edge detection.
  - **Feature Extraction & Matching:** Keypoint detection, descriptors, visual feature tracking, image stitching.
  - **Classical Computer Vision Applications:** Lane line detection, panorama creation, color space manipulation.
  - **Object Detection & Advanced Vision:** Convolutional architectures, object detection algorithms, and practical projects.
    
---

## 📁 Repository Structure

```text
ITI---CV/
├── Day 2/
├── Day 3/
├── Day 4/
├── Day 5/
│   ├── LAB/
│   │   └── CV Lab 1.ipynb
│   └── LEC/
│       └── CV lec 1.ipynb
├── Day 6/
├── Day 7/
├── Day 9/
├── Day 10/
├── Day 12/
├── Day 13/
├── Day 14/
├── Day 15/
├── Project_1/             # Real-time Analog Clock
├── Project_2/             # Interactive OpenCV Snake Game
├── Lane line .ipynb       # Interactive Lane Line Detection Pipeline
└── two stitching.ipynb    # SIFT-based Multi-Image Panorama Stitching
```

---

## 🚀 Featured Projects & Interactive Labs

### 🕒 Project 1: Real-Time Dynamic Analog Clock (`Project_1`)
* **Description:** Renders a fully functional analog clock using OpenCV drawing functions and trigonometric calculations (`math.sin` / `math.cos`) to position time hands according to system time (`datetime`).
* **Key Concepts:** Geometric primitives, trigonometric coordinate mapping, dynamic frame rendering.

### 🐍 Project 2: OpenCV Snake Game (`Project_2`)
* **Description:** An interactive Snake game built completely inside OpenCV windows. Features dynamic target placement, collision detection, real-time score tracking, and automated bot movement towards food.
* **Key Concepts:** Event loop handling, positional coordinate tracking, frame buffer re-initialization.

### 🛣️ Lane Line Detection (`Lane line .ipynb`)
* **Description:** Builds a complete vision pipeline for road lane detection:
  1. **Dynamic Canny Edge Tuning:** Interactive trackbars to adjust Canny hysteresis thresholds.
  2. **ROI & Hough Lines:** Masking region of interest followed by trackbar parameter tuning for `HoughLinesP` (`threshold`, `minLineLength`, `maxLineGap`).
  3. **Video Stream Processing:** Extends the tuned pipeline to run real-time lane detection across video feeds.

### 🖼️ Image Stitching & Panorama Creation (`two stitching.ipynb`)
* **Description:** Automatic image alignment and stitching pipeline using keypoint descriptors.
* **Key Concepts:** SIFT feature extraction (`cv2.SIFT_create`), Brute-Force feature matching (`BFMatcher`), Homography estimation via RANSAC (`cv2.findHomography`), and perspective warping (`cv2.warpPerspective`).

---

## ⚙️ How to Run

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Usama-Zidan/ITI---CV.git](https://github.com/Usama-Zidan/ITI---CV.git)
   cd ITI---CV
   ```

2. **Install Dependencies:**
   ```bash
   pip install numpy opencv-python matplotlib
   ```

3. **Run Notebooks / Scripts:**
   ```bash
   jupyter notebook "Lane line .ipynb"
   ```

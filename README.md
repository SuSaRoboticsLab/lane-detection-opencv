# Real-Time Lane Detection using OpenCV

## Overview

This project implements a real-time lane detection system using Python and OpenCV for autonomous robotic navigation applications.

The system processes camera input and detects lane boundaries for intelligent path following and autonomous movement.

---

# Features

- Real-time lane detection
- OpenCV image processing
- Edge detection
- Region of interest masking
- Hough Transform line detection
- Autonomous navigation foundation

---

# Technologies Used

- Python
- OpenCV
- NumPy

---

# Project Structure

```bash
lane-detection-opencv/
│
├── src/
├── images/
├── videos/
├── results/
├── requirements.txt
└── README.md
```

---

# How It Works

1. Capture image/video frame
2. Convert image to grayscale
3. Apply Gaussian blur
4. Perform Canny edge detection
5. Apply region masking
6. Detect lane lines using Hough Transform
7. Display final lane output

---

# Installation

```bash
git clone https://github.com/SuSaRoboticsLab/lane-detection-opencv.git

cd lane-detection-opencv

pip install -r requirements.txt
```

---

# Future Improvements

- ROS2 integration
- Real-time robotic steering
- Curved lane prediction
- Traffic sign recognition
- Embedded deployment on Raspberry Pi

---

# Applications

- Autonomous robots
- Self-driving systems
- Intelligent navigation
- AI robotics research

## Lane lines detection using Python and OpenCV
This project focuses on developing a robust lane line detection system aimed at autonomous driving and Advanced Driver Assistance Systems (ADAS). The project uses Python and OpenCV to detect and track lane lines accurately under varying environmental conditions, ensuring safer navigation.

## About
The Lane Line Detection system identifies road lane lines in real-time to support autonomous vehicles and ADAS. The project addresses challenges like lighting variations, road curvature, and noise through advanced image processing techniques such as the Canny edge detection and Hough Transform. The aim is to provide an efficient and reliable solution adaptable to diverse driving environments and lane styles.

## Features
-Edge Detection: Implements the Canny edge detection algorithm to highlight lane boundaries. -Line Detection: Uses Hough Transform to detect straight lane lines. -Real-World Adaptability: Handles varying environmental conditions like shadows, fog, and road curvature. -Region of Interest (ROI) Masking: Focuses on the relevant road area to reduce processing overhead. -Lane Extrapolation: Smooths gaps in lane lines using slope and intercept averaging.

## Requirements
Hardware:

NVIDIA GeForce GTX 1650 (for GPU acceleration) 8 GB RAM 12th Gen Intel Core i5 Processor Software:

Python 3.8 (primary development language) Anaconda for managing dependencies OpenCV 3.1.0 for image and video processing tasks

## System Architecture
Preprocessing: Converts images to grayscale and applies Gaussian blur to reduce noise. Edge Detection: Identifies lane edges using the Canny algorithm. ROI Selection: Masks the road area using a trapezoidal region. Line Detection: Detects lane lines using Hough Transform. Extrapolation: Averages detected lines to form continuous lane boundaries.


## Output

![image](https://github.com/user-attachments/assets/bfe8a602-2e8e-428a-b636-82781622b5d1)



## Results and Impact
Output Type: Visual overlay of detected lane lines on the original video or image.

Performance: Works well under normal road conditions and daylight, but struggles with tight curves and extreme lighting.

Strengths: Real-time detection, efficient handling of straight lanes, and minimal delay.

Limitations: Detection accuracy drops in low-light and extreme weather scenarios.

## Articles published / References
Noor Jannah Zakaria et al., "Lane Detection in Autonomous Vehicles: A Systematic Review," IEEE Access, 2023.

LVLane: "Deep Learning for Lane Detection and Classification in Challenging Conditions," ArXiv, 2023.

"Robust Lane Detection Through Self Pre-Training With Masked Sequential Learning," IEEE Xplore, 2023.




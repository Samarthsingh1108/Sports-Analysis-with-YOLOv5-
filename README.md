# Sports Analysis with YOLOv5

A real-time football analytics system using YOLOv5 and OpenCV to detect and track players, referees, and the ball. The project extracts key performance metrics such as player speed, distance covered, and ball possession, enabling detailed performance and tactical analysis.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Applications](#applications)
- [Future Work](#future-work)
- [License](#license)

---

## Overview

This project leverages deep learning and computer vision to analyze football matches from video input. YOLOv5 is used for object detection, and OpenCV is employed for processing and tracking. The system computes player dynamics and spatial behavior to provide insights into gameplay.

---

## Features

- Detection of players, referees, and ball using YOLOv5
- Tracking of player movements frame-by-frame
- Speed and distance estimation for individual players
- Ball possession tracking between teams
- Perspective transformation for accurate field analysis
- Works with recorded video or live streams

---

## Technologies Used

- Python 3.x  
- [YOLOv5](https://github.com/ultralytics/yolov5) (PyTorch)  
- OpenCV  
- NumPy  
- Pandas  
- Matplotlib

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sports-analysis-yolov5.git
   cd sports-analysis-yolov5

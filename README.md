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
   

## Project Structure


sports-analysis-yolov8x/
│
├── videos/                 # Input video files
├── output/                 # Output videos with analysis
├── analyze.py              # Main script for detection and analysis
├── tracking.py             # Player and ball tracking logic
├── utils.py                # Perspective transform, speed, distance functions
├── requirements.txt        # Required Python libraries
└── README.md

---

## Results


-Annotated videos with object labels (players, ball, referees)
-Player speed and movement trajectories
-Ball possession timeline and team-wise stats
-CSV and graphical output of key performance indicators

---

## Applications


-Tactical decision-making for coaches
-Live performance metrics for broadcasters
-Post-match analysis and training feedback
-Data visualization and engagement for fans

---

## Future Enhancements


-Real-time streaming integration
-Integration with a dashboard or web interface
-Enhanced accuracy for ball-pass detection
-Multi-camera support and player re-identification


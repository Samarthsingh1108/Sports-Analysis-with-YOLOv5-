# Sports Analysis with YOLOv5

A real-time football analytics system using YOLOv5 and OpenCV to detect and track players, referees, and the ball. The project extracts key performance metrics such as player speed, distance covered, and ball possession, enabling detailed performance and tactical analysis.

## Table of Contents

- [Overview](#overview)
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Applications](#applications)
- [Future Work](#future-work)
- [Input/Output Images](#input/output-images)



## Overview

This project leverages deep learning and computer vision to analyze football matches from video input. YOLOv5 is used for object detection, and OpenCV is employed for processing and tracking. The system computes player dynamics and spatial behavior to provide insights into gameplay.

## Introduction

The landscape of sports analytics has evolved significantly with the advent of artificial intelligence and computer vision. Traditional methods of performance evaluation and tactical assessment often relied on manual annotation and subjective interpretation, which are time-consuming and prone to human error. This project aims to automate and enhance football match analysis using state-of-the-art object detection and visual tracking techniques.

Sports Analysis with YOLOv8x is a comprehensive system designed to extract actionable insights from football match footage by leveraging the power of deep learning and image processing. At its core, the project uses YOLOv8x (You Only Look Once version 8, extra-large model) for real-time object detection of players, referees, and the ball. The model’s high accuracy and speed make it ideal for handling dynamic sports environments with multiple fast-moving entities.

The system is capable of tracking players throughout the match, estimating their speed and distance covered using frame-to-frame coordinate shifts and video metadata. It also applies perspective transformation to map camera footage to a real-world field layout, enabling precise spatial calculations. Additionally, the project introduces a simplified approach to estimate ball possession by analyzing proximity and movement patterns between the ball and players.

By combining computer vision and sports science, this project delivers an intelligent platform for analyzing player performance, understanding game dynamics, and assisting coaches, analysts, and broadcasters. It reduces the manual overhead of video review while providing richer, data-driven perspectives of the game.

This framework can be extended to support live-streamed matches, integrated into tactical dashboards, or adapted to other sports such as basketball, hockey, or rugby. It serves as a stepping stone towards building fully autonomous sports analytics systems that complement human expertise with machine intelligence.


## Features

- Detection of players, referees, and ball using YOLOv5
- Tracking of player movements frame-by-frame
- Speed and distance estimation for individual players
- Ball possession tracking between teams
- Perspective transformation for accurate field analysis
- Works with recorded video or live streams


## Technologies Used

- Python 3.x  
- [YOLOv5](https://github.com/ultralytics/yolov5) (PyTorch)  
- OpenCV  
- NumPy  
- Pandas  
- Matplotlib


## Installation

1. Clone the repository:
  pip install git+https://github.com/ultralytics/ultralytics.git@main
   

## Project Structure


![image](https://github.com/user-attachments/assets/a574aba4-d712-461d-954c-249eaab85afd)


## Results


- Annotated videos with object labels (players, ball, referees)
- Player speed and movement trajectories
- Ball possession timeline and team-wise stats
- CSV and graphical output of key performance indicators


## Applications


- Tactical decision-making for coaches
- Live performance metrics for broadcasters
- Post-match analysis and training feedback
- Data visualization and engagement for fans


## Future Enhancements


- Real-time streaming integration
- Integration with a dashboard or web interface
- Enhanced accuracy for ball-pass detection
- Multi-camera support and player re-identification


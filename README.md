# Football Match Analysis using Computer Vision

https://github.com/user-attachments/assets/57c12f40-8175-43d2-a11b-9da0d7e6bb8b

## Overview

This project is a computer vision-based system for analyzing football match videos. It leverages deep learning to detect and track players, the ball, and key game statistics, providing insights into player movements, team possession, and camera dynamics. The system uses YOLOv8-X, fine-tuned on a Roboflow dataset for 100 epochs, to ensure high accuracy in player and ball detection.

## Features

- **Player and Ball Detection**: Identifies players and the ball in the video feed.
- **Team Classification**: Differentiates players based on team colors.
- **Player Tracking**: Tracks each player's movement throughout the game.
- **Speed and Distance Calculation**: Computes each player's speed and distance covered.
- **Ball Possession Analysis**: Determines team-wise possession of the ball.
- **Camera Movement Estimation**: Analyzes camera panning and zooming behavior.

## Technology Stack

- **Deep Learning Model**: YOLOv8-X (fine-tuned on Roboflow dataset, 100 epochs)
- **Frameworks**: PyTorch, OpenCV
- **Development Environment**: Python, Jupyter Notebook


### Resources

[Drive Link](https://drive.google.com/drive/folders/1P5tNyfVrku7D3JmmNOwMXsLi9RubhZpH?usp=drive_link)


## Results

The model provides real-time analysis of:

- Player tracking with speed and distance metrics
- Team-wise ball possession percentage
- Camera movement trends

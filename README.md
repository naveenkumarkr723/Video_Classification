# Sports Action Recognition Using 3D CNN

This project is designed for recognizing different types of sports actions in videos using a 3D Convolutional Neural Network (CNN). The model is trained on videos of different sports and is capable of classifying a given video into one of the following sports categories:

- Cricket
- Soccer
- Baseball
- Basketball

The project uses TensorFlow/Keras to build and train the model, and OpenCV to handle video preprocessing.

## Table of Contents

- [Overview](#overview)
- [Prerequisites] [https://www.tensorflow.org/tutorials/video/video_classification](url)
- Setup Instructions

Install the Tensorflow version > 2.1.0

- [Dataset](#dataset) [https://drive.google.com/drive/folders/111Egq8sMVAi-matPbby8ZhRZSV0HiLsE?usp=drive_link](url)


## Overview

The goal of this project is to develop a model that can recognize sports actions from a video. It uses 3D CNNs to process video frames and extract features across both spatial and temporal dimensions.

The system takes in a video, processes it into frames, and uses a 3D Convolutional Neural Network to classify the action as one of the predefined sports.

## Prerequisites

Ensure that you have the following installed:

- Python 3.x
- TensorFlow (2.x recommended)
- OpenCV
- NumPy
- Scikit-learn

You can install the required dependencies using `pip`:

```bash
pip install tensorflow opencv-python numpy scikit-learn

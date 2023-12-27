# Line Following Robot with Neural Network



https://github.com/AJDevCode/Line-Following-Robot/assets/67168409/09af6c86-23f5-4bb1-84da-b0a03835bba1



## Description
The Line Following Robot with Neural Network is a project designed to create a robot that can autonomously follow a line. Initially, the robot must be manually driven over the line to collect training data for a neural network. After sufficient training data has been provided, the robot can use the neural network to navigate and follow the line autonomously.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Features](#features)
- [Technologies Used](#technologies-used)


## Prerequisites
Before you begin, ensure you have the following requirements:

- **Line Following Robot**: Set up a robot with sensors for line following.

- **Ros2 Humble**: Ros2 humble needs to be setup on linux

- **Python**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

- **Neural Network Libraries**: Install library TensorFlow for neural network training.

## Installation
Follow these steps to set up the Line Following Robot with Neural Network:

### Step 1: Clone the Repository
```bash
git clone https://github.com/AJDevCode/line-following-robot.git
```
### Step 2: Configure Robot Sensors
Set up and configure the robot's sensors for line following.

## Usage
To use the Line Following Robot with Neural Network, execute the following command:

``` bash
python line_following_robot.py
```
The robot will be manually driven over the line initially to collect training data. After training, the robot can autonomously follow the line.

Training
Follow these steps to train the neural network:

Step 1: Collect Training Data
Manually drive the robot over the line to collect training data. 

Step 2: Train the Neural Network
Run the training script to train the neural network:


## Features
The Line Following Robot with Neural Network offers the following key features:

Manual driving for collecting training data.

Neural network-based line-following capabilities.

Autonomous line following once trained.

## Technologies Used
Python

Neural Network (TensorFlow)

Ros2 Humble

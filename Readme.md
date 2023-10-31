# Drowsiness Detector

## Overview
The Drowsiness Detector is a real-time monitoring tool designed to detect and alert users when signs of drowsiness are detected. This application utilizes computer vision and machine learning techniques to analyze live video streams, identifying potential indicators of drowsiness in the user's facial expressions and eye movements. It is particularly useful for drivers, machinery operators, and individuals in other attention-critical roles, helping to enhance safety and reduce the risk of accidents caused by fatigue.

## Features

- **Real-Time Monitoring**: Continuously analyze the video stream from the user's webcam to detect signs of drowsiness.
- **Eye Blink Detection**: Utilize advanced algorithms to monitor the user's eye blinks, with a high blink rate or prolonged eye closure triggering a drowsiness alert.
- **Facial Expression Analysis**: Examine facial expressions to identify other signs of drowsiness or fatigue.
- **Alert System**: Notify the user with visual and auditory alerts when signs of drowsiness are detected.
- **Customizable Sensitivity**: Adjust the sensitivity of the detection algorithms to accommodate different users and environments.
- **Usage Statistics**: Log usage data and drowsiness detection statistics for further analysis and personalized adjustments.
- **User-Friendly Interface**: Provide a simple and intuitive interface, making it easy for users to operate the system.

## How It Works

The Drowsiness Detector operates by analyzing video input from the user's webcam. Using a combination of computer vision techniques and machine learning models, the application assesses the user’s eye blink rate, eye closure duration, and facial expressions to determine their level of alertness. When signs of drowsiness are detected, the system triggers an alert to capture the user’s attention and encourage them to take a break or engage in activities to re-energize.

## Installation and Usage

Detailed instructions for installation, configuration, and usage will be provided in the [Installation Guide](./docs/installation_guide.md) and [User Manual](./docs/user_manual.md).

## Requirements

- A computer with a webcam
- Python 3.6 or later
- Required Python packages (listed in `requirements.txt`)

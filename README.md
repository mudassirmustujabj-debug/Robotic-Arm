# AI-Assisted 4-DOF Robotic Arm

An intelligent robotic arm integrating computer vision, embedded systems, and AI for autonomous object detection and manipulation.

This project combines Python, Arduino, YOLOv8, and a locally-hosted language model (Ollama) to create an interactive robotics system capable of understanding natural-language commands and performing pick-and-place operations.

---

## Features

- Custom 4-DOF Mechanical Design
- YOLOv8 Object Detection
- Arduino Servo Control
- Python-Arduino Serial Communication
- AI Natural Language Commands
- Autonomous Pick-and-Place Experiments

---

## Hardware

- Arduino Uno
- MG996R Servo Motors
- SG90 Servo Motors
- External Power Supply
- Custom Acrylic Arm

---

## Software Stack

### AI

- Ollama
- Local LLM

### Computer Vision

- OpenCV
- YOLOv8

### Embedded

- Arduino
- Servo Library

### Programming

- Python
- C++

---

## System Architecture

```
Camera

↓

YOLOv8

↓

Python Controller

↓

LLM Decision Layer

↓

Serial Communication

↓

Arduino

↓

Servo Motors
```

---

## Capabilities

- Detect Objects
- Understand Voice/Text Commands
- Calculate Pick Positions
- Control Multiple Servos
- Execute Autonomous Movement

---

## Installation

Clone repository.

```bash
git clone https://github.com/mudassirmustujabj-debug/Robotic-Arm.git
```

Install dependencies.

```bash
pip install -r requirements.txt
```

Upload Arduino firmware.

Run Python application.

---

## Future Improvements

- Inverse Kinematics
- Path Planning
- Object Tracking
- Reinforcement Learning
- Gripper Force Feedback
- ROS2 Integration

---

## Demonstration

The project was demonstrated during the Bahria University Robotics admission interview, contributing to a 6th-place merit ranking.

---

## Author

Syed Mudassir Mustujab

GitHub:
https://github.com/mudassirmustujabj-debug

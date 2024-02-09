# YOLOv8n Plastic Detection Model

This project implements a plastic detection model using YOLOv8n (You Only Look One Version 8 Nano) with the Ultralytics library. The model is trained on a custom dataset from Roboflow for detecting plastic objects in images.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Custom Training](#custom-training)
- [Validation](#validation)
- [Prediction](#prediction)
- [Results](#results)
- [Contribution](#contribution)
- [License](#license)

## Introduction

Plastic pollution is a significant environmental issue, and this project focuses on detecting plastic objects in images using the YOLOv8n object detection model. The model is trained on a custom dataset obtained from Roboflow, enabling accurate identification and localization of plastic items.

## Requirements

- NVIDIA GPU
- Python 3.x
- Ultralytics
- YOLOv8n
- OpenCV
- Roboflow

## Installation

1. Check for the availability of the NVIDIA GPU using the command: `!nvidia-smi`.
2. Install Ultralytics version 8.0.28 and other dependencies:

   ```bash
   !pip install ultralytics==8.0.28

## Install roboflow:

   ```bash
   !pip install roboflow


# YOLO11m–MiDaS Framework for Real-Time Pothole Detection and Navigation Assistance

## Overview

This project presents an intelligent pothole detection and navigation assistance framework that combines YOLO11m object detection with MiDaS depth estimation. The system is capable of detecting potholes, estimating their distance, evaluating risk severity, determining safe navigation directions, and generating adaptive voice guidance.

The proposed framework integrates:

- CLAHE-based image enhancement
- YOLO11m pothole detection
- MiDaS depth estimation
- Dynamic risk scoring
- Direction analysis
- Adaptive voice guidance

## Features

- Real-time pothole detection
- Monocular depth estimation
- Distance estimation without LiDAR
- Dynamic pothole risk assessment
- Navigation guidance generation
- Voice alert support
- Road safety assistance for pedestrians
- Support for visually impaired users

## Dataset

Source: Roboflow Pothole Dataset

Dataset Statistics:

- Training Images: 6091
- Validation Images: 2094
- Test Images: 1055

## Model Configuration

Model: YOLO11m

Training Parameters:

- Epochs: 70
- Image Size: 640 × 640
- Batch Size: 8
- Optimizer: AdamW
- Learning Rate: 0.001
- Cosine Learning Rate Scheduler
- Mosaic Augmentation
- MixUp Augmentation
- HSV Augmentation

## Experimental Results

### Validation Set

| Metric | Value |
|----------|----------|
| Precision | 80.72% |
| Recall | 70.54% |
| F1-Score | 75.29% |
| mAP@50 | 77.97% |
| mAP@50:95 | 45.33% |

### Test Set

| Metric | Value |
|----------|----------|
| Precision | 78.84% |
| Recall | 73.54% |
| F1-Score | 76.10% |
| mAP@50 | 78.48% |
| mAP@50:95 | 47.29% |

## Project Workflow

Input Image
↓
CLAHE Enhancement
↓
YOLO11m Detection
↓
MiDaS Depth Estimation
↓
Distance Calculation
↓
Risk Scoring
↓
Direction Analysis
↓
Voice Guidance
↓
Output Generation

## Applications

- Intelligent Transportation Systems
- Smart City Infrastructure
- Road Condition Monitoring
- Autonomous Navigation
- Pedestrian Assistance Systems
- Assistive Technology for Visually Impaired Users

## Author

Bharath
M.Tech Computer Science and Engineering (Data Science)
VIT Vellore

# 🎭 Real-Time Facial Emotion Detection with YOLOv8

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Ultralytics YOLOv8](https://img.shields.io/badge/YOLOv8-8.0.196-red)](https://github.com/ultralytics/ultralytics)
[![Roboflow](https://img.shields.io/badge/Roboflow-1.1.27-orange)](https://roboflow.com)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.8.1-green)](https://opencv.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A production-ready computer vision system for real-time facial emotion detection. This project implements a complete ML pipeline from dataset curation to real-time deployment, achieving high-accuracy emotion classification at 30+ FPS.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Quick Start](#quick-start)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Technical Details](#technical-details)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 Project Overview

Developed during the **Hyperbyte AI Bootcamp (September 2024)** under the guidance of instructors **Zad Chin** and **Jay Yen Lim**, this project demonstrates a complete computer vision workflow:

- **Dataset Curation**: Collected and annotated facial expression data using Roboflow
- **Model Development**: Fine-tuned YOLOv8 for emotion detection
- **Real-time Deployment**: Built a webcam pipeline with OpenCV
- **Performance Optimization**: Tuned confidence thresholds for optimal accuracy

**Key Achievement**: Built an end-to-end emotion detection system achieving **0.78 mAP@0.5** with real-time inference capabilities.

## ✨ Features

- **Real-time Performance**: 30+ FPS on standard hardware
- **Multi-Emotion Detection**: Classifies 7 emotion categories
- **Complete Pipeline**: Data → Training → Evaluation → Deployment
- **Professional Visualization**: Comprehensive training metrics and analysis
- **Easy Configuration**: Command-line interface with sensible defaults
- **Webcam Integration**: Live emotion detection with bounding box overlay

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- NVIDIA GPU (recommended for training) with CUDA 11.8
- Webcam (for real-time inference)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/Emotion-Detection-YOLOv8.git
cd Emotion-Detection-YOLOv8
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Set up environment variables**

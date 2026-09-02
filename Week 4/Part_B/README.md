# Week 4, Part B: Deep Learning Architectures

## Overview
This module implements a suite of deep learning architectures to process structured, spatial, and sequential data using TensorFlow/Keras. It culminates in a production grade, decoupled object detection system deployed on edge infrastructure.

## Architectures Implemented
1.  **ANN (Artificial Neural Network):** Fully connected multi-layer perceptron for tabular binary classification (Breast Cancer diagnostics).
2.  **CNN (Convolutional Neural Network):** Spatial feature extraction network utilizing Conv2D and MaxPooling layers for image classification (Fashion-MNIST).
3.  **RNN (Recurrent Neural Network):** Sequence modeling utilizing Long Short-Term Memory (LSTM) gating mechanisms for natural language sentiment analysis (IMDB).
4.  **YOLOv8 (Object Detection - NexGen Vision QA):** A production-grade implementation deployed via ONNX and FastAPI, bypassing standard PyTorch execution for zero-latency real-time inference.

## Live Deployment (YOLOv8 Inference)
*   **Frontend (SCADA Interface):** [optics.nexgenbuilds.tech](https://optics.nexgenbuilds.tech)
*   **Backend (FastAPI Engine):** [nexgen-vision-qa.onrender.com/docs](https://nexgen-vision-qa.onrender.com/docs#/)
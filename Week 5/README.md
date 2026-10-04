# Week 5: Deep Learning (Spatial vs. Sequential Architectures)

## Project: NexGen NeuroVision
**Lead Engineer:** Saad Ullah  
**Instructor:** Mr. Zaheen Ahmad  

## Executive Summary
This directory contains the core academic deliverables for the Week 5 Deep Learning task. It evaluates spatial versus sequential neural networks applied to raw medical imagery using a perfectly balanced 7,200-image dataset of Brain MRI scans. 

The empirical telemetry proves that the fine-tuned CNN (ResNet50) fundamentally outperforms sequential architectures (RNN, LSTM) for pixel based classification tasks by preserving localized spatial geometry.

## Dedicated Production Repository
Because the winning ResNet50 architecture was fully containerized and deployed into a production grade pipeline (FastAPI Backend + Next.js Frontend), the complete codebase, Docker orchestration, and ONNX execution engines are hosted in a dedicated repository to prevent bloating this portfolio.

*   **Full Source Code & Architecture Blueprint:** [github.com/saadullah-cs/NexGen-NeuroVision](https://github.com/saadullah-cs/NexGen-NeuroVision)
*   **Live Clinical Interface:** [neuro.nexgenbuilds.tech](https://neuro.nexgenbuilds.tech)

## Local Submissions
The files enclosed in this directory fulfill the required deliverables for Task 5:
1.  `23MDBCS404_Saad_Ullah_Week5_Task5.ipynb`: The isolated model training, comparative evaluation, and ROC/AUC generation pipeline.
2.  `23MDBCS404_Saad_Ullah_Week5_Task5.pdf`: The formal comparative analysis report detailing hyperparameters, confusion matrices, and the architectural conclusion.
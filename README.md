# Emotion Recognition using CNN

## Overview

This project implements a Convolutional Neural Network (CNN) to classify
human facial expressions into multiple emotion categories.

------------------------------------------------------------------------

## Dataset

Dataset used: FER (Kaggle)

Classes: - Angry\
- Disgust\
- Fear\
- Happy\
- Neutral\
- Sad\
- Surprise

------------------------------------------------------------------------

## Project Structure

emotion-recognition-project/ ├── emotional_recognation.ipynb ├──
outputs/

------------------------------------------------------------------------

## Model

-   CNN with Conv layers, BatchNorm, ReLU, MaxPool

------------------------------------------------------------------------

## Training

-   Loss: CrossEntropyLoss\
-   Optimizer: Adam\
-   LR: \~0.0005--0.0007\
-   Epochs: up to 50

------------------------------------------------------------------------

## Results

-   Validation Accuracy: \~70%

------------------------------------------------------------------------

## Visualization

Confusion Matrix, Accuracy Curve, Loss Curve in outputs/

------------------------------------------------------------------------

## Run

pip install -r requirements.txt\
jupyter notebook emotional_recognation.ipynb

------------------------------------------------------------------------

## Author

Sarvesh Patil

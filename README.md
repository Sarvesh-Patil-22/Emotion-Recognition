# Emotion Recognition using CNN

## Overview

This project implements a Convolutional Neural Network (CNN) to classify
human facial expressions into multiple emotion categories.

The goal is to automatically recognize emotions from facial images.

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

Images are grayscale (48x48) and include \~35,000 samples.

------------------------------------------------------------------------

## Project Structure

emotion-recognition-project/ ├── emotional_recognation.ipynb ├──
outputs/

------------------------------------------------------------------------

## Model Architecture

-   Convolutional Layers\
-   Batch Normalization\
-   ReLU Activation\
-   MaxPooling\
-   Fully Connected Layers

------------------------------------------------------------------------

## Training Details

-   Loss: CrossEntropyLoss\
-   Optimizer: Adam\
-   Learning Rate: \~0.0005--0.0007\
-   Epochs: up to 50

------------------------------------------------------------------------

## Results

-   Validation Accuracy: \~70%

------------------------------------------------------------------------

## Challenges and Limitations

-   Some emotions are visually very similar (e.g., fear vs surprise)
-   Dataset contains noisy and low-resolution images (48x48)
-   Model struggles with subtle facial expressions
-   Class imbalance affects performance

------------------------------------------------------------------------

## Why Model Does Not Reach Higher Accuracy

-   Limited resolution reduces feature quality
-   Simple CNN architecture compared to modern models
-   No transfer learning used
-   Some classes overlap in feature space

------------------------------------------------------------------------

## Evaluation Metrics

-   Accuracy\
-   Confusion Matrix\
-   Training & Validation Curves

------------------------------------------------------------------------

## Visualization

Confusion Matrix, Accuracy Curve, and Loss Curve are available in the
outputs/ folder.

------------------------------------------------------------------------

## How to Run

pip install -r requirements.txt\
jupyter notebook emotional_recognation.ipynb

------------------------------------------------------------------------

## Author

Sarvesh Patil

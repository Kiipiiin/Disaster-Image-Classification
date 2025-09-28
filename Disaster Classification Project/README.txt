# Disaster Image Classification – Deep Learning Project

This project focuses on classifying disaster images into multiple categories using deep learning. It demonstrates data cleaning, anomaly detection, and training a Convolutional Neural Network (CNN) with EfficientNetB0


## Dataset
- Dataset Link: https://drive.google.com/drive/folders/1pDYH-m2dHS_bZ34VBslYP8Xi9NshIZH_?usp=sharing
- train: contains training images.
- val: contains validation images.
- test: contains testing images.
- train_outlier: contains all the out of context images.

## Project Overview

- **Goal:** Classify disaster images accurately. 
- **Dataset:** Disaster dataset with train/validation/test split and multiple categories.
- **Methods:**
  - SOM (Self-Organizing Map) clustering to detect and remove anomalous images.
  - Removing anomalies (out of context images) from each categories
  - Standard Preprocessing for image classification
  - EfficientNetB0 as backbone CNN with GlobalAveragePooling and dense output layer.

## Results

- Accuracy improved from **80% to 86%** after anomaly removal and preprocessing.
- Model is robust except for detecting earthquake (imbalanced class)


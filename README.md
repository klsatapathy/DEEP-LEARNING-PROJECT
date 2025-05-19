# DEEP-LEARNING-PROJECT



# Image Classification using PyTorch

## Project Overview
This project demonstrates an end-to-end image classification pipeline using PyTorch on the CIFAR-10 dataset. The implementation includes:

1. Data loading and preprocessing with transformations and augmentation
2. A custom CNN architecture with batch normalization and dropout
3. Training with learning rate scheduling
4. Performance evaluation and visualization
5. Prediction analysis and confidence scoring

## Key Features

- **Data Augmentation**: Random crops and horizontal flips for better generalization
- **Model Architecture**: 
  - Sequential CNN blocks with BatchNorm and ReLU
  - Dropout layers to prevent overfitting
- **Training Process**:
  - Adam optimizer with ReduceLROnPlateau scheduler
  - Cross-entropy loss
  - GPU acceleration support
- **Evaluation**:
  - Training loss and test accuracy tracking
  - Visualization of learning curves
  - Sample predictions with confidence scores

## Technical Details

- **Dataset**: CIFAR-10 (10 classes, 32x32 color images)
- **Model**: Custom CNN achieving ~88% test accuracy
- **Training**:
  - Batch size: 128
  - Learning rate: 0.001
  - Epochs: 25
  - Data augmentation: RandomCrop, RandomHorizontalFlip
  - Normalization using CIFAR-10 statistics

## Usage

The notebook provides complete code for:
1. Loading and preprocessing data
2. Defining and training the model
3. Evaluating performance
4. Visualizing results
5. Making predictions with confidence scores

## Requirements

- PyTorch
- torchvision
- matplotlib
- numpy
- tqdm

The implementation leverages GPU acceleration when available and includes comprehensive visualization of both training progress and model predictions.

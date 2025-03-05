# Leukemia Cell Classification using Deep Learning

## Project Overview

This project implements a deep learning approach to classify leukemia blast cells from microscopic images. The system uses multiple convolutional neural network architectures to detect Acute Lymphoblastic Leukemia (ALL) from blood cell images with high accuracy.

## Live Demo

A working demo of this application can be accessed at: [https://huggingface.co/spaces/SanjayChoodamani/CNN](https://huggingface.co/spaces/SanjayChoodamani/CNN)


## Features

- **Multi-model implementation**: Utilizes 5 state-of-the-art deep learning models:
  - VGG19
  - InceptionV3
  - MobileNetV2
  - DenseNet201
  - ResNet101V2
- **Advanced image processing**: Implements adaptive sharpening and image augmentation
- **User-friendly GUI**: Easy-to-use interface for image classification
- **High accuracy classification**: Distinguishes between leukemia blast cells and normal cells

## Dataset

The project uses the Acute Lymphoblastic Leukemia Image Database (ALL-IDB):
- **ALL-IDB1**: Contains microscopic images with blast and normal cells

## Technical Implementation

- Image standardization to 224×224 pixels
- Adaptive sharpening for better feature extraction
- Transfer learning with pre-trained CNN architectures
- Early stopping and model checkpoints for optimal training
- Data augmentation to enhance model generalization

## Model Performance

Each model has been evaluated on the ALL-IDB dataset:

- **DenseNet201**: Highest overall accuracy
- **InceptionV3**: Best balance between accuracy and computational efficiency
- **VGG19**: Strong feature extraction for blast cell identification
- **MobileNetV2**: Optimized for efficiency, suitable for deployment on resource-constrained devices
- **ResNet101V2**: Excellent performance on challenging cases

## GUI Usage

The project includes a graphical user interface that allows users to:
- Upload blood cell images
- Choose the preferred classification model
- View classification results with confidence scores
- Process multiple images in batches


## About Acute Lymphoblastic Leukemia (ALL)

ALL is a type of cancer that affects white blood cells. Early detection is crucial for successful treatment. This project aims to assist medical professionals in the rapid and accurate identification of ALL blast cells.
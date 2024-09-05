# Potato Leaf Disease Classification

## Project Overview
This project focuses on classifying potato leaf diseases using advanced computer vision techniques and convolutional neural networks (CNNs). By leveraging pre-trained model architectures such as VGG16 and ResNet50, the project aims to provide an accurate solution for detecting crop diseases, which is crucial for precision agriculture.

## Table of Contents
1. [Project Description](#project-description)
2. [Data Preprocessing](#data-preprocessing)
3. [Model Architecture](#model-architecture)
4. [Performance Evaluation](#performance-evaluation)
5. [Visualizations](#visualizations)

### Project Description
This project utilizes convolutional neural networks to identify and classify diseases from leaf images. The diseases targeted are:

- Apple___healthy
- Apple___Apple_scab
- Apple___Black_rot
- Apple___Cedar_apple_rust

### Data Preprocessing
The preprocessing steps include:

- Image normalization
- Histogram equalization
- Conversion of labels to numerical format

The dataset is split into training and validation sets, and TensorFlow data generators are created to feed the models.

### Model Architecture
Two CNN architectures are employed:

- **VGG16**: A popular CNN model pre-trained on ImageNet, adapted with new layers for disease classification.
- **ResNet50**: Another robust CNN model pre-trained on ImageNet, also customized for classification tasks.

### Performance Evaluation
Model performance is evaluated using metrics such as:

- Accuracy
- Recall
- Precision
- F1 Score

Results indicate that ResNet50 outperforms VGG16 in terms of accuracy and F1 score.

### Visualizations
Visualizations include:

- Training and validation loss curves
- Confusion matrix
- AUC-ROC curves for each class

These visualizations help in the detailed analysis of model performance.

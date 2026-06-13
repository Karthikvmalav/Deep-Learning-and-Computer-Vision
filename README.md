# Deep Learning and Computer Vision

A collection of machine learning and computer vision projects exploring deep neural networks, image understanding, image generation, and tree-based learning methods.

This repository contains implementations of convolutional neural networks, multi-task learning systems, image colorization models, decision trees, and random forests, together with extensive experimentation and model analysis.

---

## Project Overview

This repository investigates multiple learning paradigms:

* Multi-Task Learning
* Computer Vision
* Image Colorization
* Classification and Regression
* Decision Trees
* Ensemble Learning
* Hyperparameter Optimization

The goal is to understand how different machine learning models learn representations, generalize to unseen data, and solve diverse prediction tasks.

---

## Projects

### 1. Multi-Task CNN

A convolutional neural network designed to simultaneously solve:

* Image Classification
* Continuous Value Regression

using a shared feature extractor and task-specific prediction heads.

#### Key Features

* Shared convolutional backbone
* Multi-head architecture
* Joint optimization with Cross-Entropy and MSE losses
* Hyperparameter exploration
* Feature map visualization
* Representation analysis

#### Dataset

* Fashion-MNIST

---

### 2. Image Colorization

An encoder-decoder convolutional architecture for automatic image colorization.

Given a grayscale image, the model predicts plausible color distributions for every pixel and reconstructs a colorized image.

#### Key Features

* Encoder-decoder CNN
* Learned upsampling using transpose convolutions
* Pixel-wise color prediction
* Color clustering
* Training and validation visualization

#### Dataset

* CIFAR-10

---

### 3. Decision Trees

Implementation and analysis of decision tree models for supervised learning tasks.

#### Topics Explored

* Information Gain
* Entropy-based Splitting
* Tree Depth Analysis
* Hyperparameter Tuning
* Model Interpretation

---

### 4. Random Forests

Ensemble learning using collections of decision trees.

#### Topics Explored

* Bootstrap Sampling
* Feature Subsampling
* Ensemble Aggregation
* Bias-Variance Tradeoff
* Performance Comparison with Single Trees

---

## Technologies

* Python
* PyTorch
* NumPy
* Scikit-Learn
* Matplotlib
* Weights & Biases (WandB)

---

## Results

Across these projects, the repository explores:

* Multi-task representation learning
* Visual feature extraction
* Image generation and reconstruction
* Ensemble learning techniques
* Hyperparameter optimization
* Model interpretability

The experiments demonstrate how different model families can be applied to classification, regression, and computer vision tasks while highlighting the trade-offs between model complexity, accuracy, and generalization.

---

## Future Work

* Vision Transformers (ViTs)
* Self-Supervised Learning
* Semantic Segmentation
* Diffusion Models
* Model Compression and Quantization
* Explainable AI Techniques

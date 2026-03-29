# Assignment 7: Exploring Specialized Neural Network Architectures

This repository contains a hands-on exploration of Convolutional Neural Networks (CNNs) for image classification using the MNIST handwritten digit dataset.

## Overview

This assignment guides you through building, training, and analyzing CNNs to understand how architectural choices impact model performance. You'll experiment with different configurations, compare CNNs to traditional feedforward networks, and reflect on how specialized architectures could enhance real-world projects.

## Learning Objectives

- Build and train CNNs for image classification
- Experiment with architectural hyperparameters (filter counts, kernel sizes)
- Visualize model training performance through accuracy and loss curves
- Compare CNN performance against feedforward neural networks
- Understand when to apply specialized architectures vs. traditional models

## File Structure

```
DSMII-Assignment-7/
├── README.md                   # This file
└── starter_notebook.ipynb      # Main assignment notebook
```

## Key Components

### Notebook Contents

The `starter_notebook.ipynb` includes:

1. **Setup & Data Loading**: Import libraries and load the MNIST dataset
2. **Baseline CNN**: Build a 2-layer convolutional network with standard hyperparameters
3. **Filter Count Experiments**: Test networks with fewer (16, 32) and more (64, 128) filters
4. **Kernel Size Experiments**: Explore 5x5 kernels and mixed kernel configurations
5. **Best Architecture**: Train your optimal configuration based on experiments
6. **Performance Visualization**: Plot accuracy and loss curves over training epochs
7. **Feedforward Comparison**: Build a traditional neural network and compare results
8. **Final Project Reflection**: Consider how specialized architectures apply to your project

## Running in VS Code

### Prerequisites

- Python 3.x
- VS Code with Jupyter extension installed
- TensorFlow, NumPy, Pandas, and Matplotlib

### Running the Notebook

1. Open the workspace in VS Code
2. Open `starter_notebook.ipynb`
3. Install dependencies by running the first code cell (pip install command)
4. Execute cells sequentially, completing the TODO sections
5. Complete analysis questions in markdown cells throughout the notebook

The notebook uses TensorFlow/Keras to build neural networks and trains them on the MNIST dataset (28x28 grayscale images of handwritten digits 0-9).

## Key Experiments

- **Baseline CNN**: 32 and 64 filters with 3x3 kernels
- **Filter Variations**: Compare 16/32 vs 64/128 filter configurations
- **Kernel Variations**: Test 5x5 kernels and mixed kernel sizes
- **Architecture Comparison**: CNN vs feedforward network on image data

## Expected Outputs

- Trained CNN models with varying architectures
- Performance metrics (accuracy, loss, training time)
- Visualization plots showing model learning over epochs
- Comparison table of different model architectures
- Written analysis of architectural choices and their impact

## Assignment Completion

Complete all TODO sections in the notebook, including:
- Model building and training code
- Analysis responses in markdown cells
- Final project reflection
- Push completed work to GitHub and submit repository link

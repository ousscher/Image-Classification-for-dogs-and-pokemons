# Image-Classification-for-dogs-and-pokemons

This repository contains the implementation of a Convolutional Neural Network (CNN) for image classification using TensorFlow. The project focuses on classifying images from the **Pokemon** and **Dog Breed** datasets. The goal is to preprocess the images, design custom CNN architectures, and evaluate their performance.

## Datasets
1. **Pokemon Image Dataset**: [Download here](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types)
2. **Dog Breed Image Dataset**: [Download here](https://www.kaggle.com/datasets/khushikhushikhushi/dog-breed-image-dataset)

## Features
- Image preprocessing: Convert RGBA to RGB, grayscale conversion, and normalization.
- Custom CNN model creation based on a configuration string.
- Training and evaluation of baseline models for:
  - Colored Pokemon images
  - Grayscale Pokemon images
  - Colored Dog Breed images
  - Grayscale Dog Breed images
- Visualization of training/validation loss and accuracy.
- Classification reports for model evaluation.

## Requirements
- Python 3.x
- Libraries: TensorFlow, NumPy, Pandas, Matplotlib, Scikit-learn, Jupyter Notebook

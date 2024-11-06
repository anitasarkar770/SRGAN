# SRGAN
Image generation using SRGAN (https://arxiv.org/pdf/1609.04802)

# Objective
1. Train a SRGAN model to reconstruct 128 X 128 dimension images from 32 X 32 dimension low resolution images.
2. Train a VGG16 classifier to classify cats and dogs using original images; train a similar classifier using generated images and compare the performance between the two.

# SRGAN Architecture

![image](https://github.com/user-attachments/assets/eca702d8-0860-45f2-95e5-66aa5d277fe8)
B = 16 in this implementation


![image](https://github.com/user-attachments/assets/a666cfd0-13e0-4e1b-a170-0aee0b810537)


# Data
Cats and Dogs data set from Kaggle
https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset

# Packages
1. Tesnorflow 2.17.0
2. Keras 3.4.1

# Config Parameters
1. Low resolution image size 32 X 32
2. Generated image size 128 X 128
3. Batch size 32
4. Number of epochs 150
Optimizers: Adam

# Notebook reference
#https://github.com/deepak112/Keras-SRGAN


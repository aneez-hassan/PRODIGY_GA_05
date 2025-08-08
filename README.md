# PRODIGY_GA_05
# Task 5: Neural Style Transfer

This project implements **Neural Style Transfer** — a technique that applies the artistic style of one image (e.g., a famous painting) to the content of another image, using deep learning.

## Overview

Neural Style Transfer uses convolutional neural networks to separate and recombine the content and style of images. This project uses PyTorch and a pretrained VGG19 model to perform style transfer.

## How to Run

1. Make sure you have the required libraries installed:
   ```bash
   pip install torch torchvision matplotlib pillow
   
Run the main script:
python neural_style_transfer.py
The code automatically downloads example content and style images, performs style transfer, and saves the output image as output.jpg.

**Files**
neural_style_transfer.py — Main implementation of the neural style transfer algorithm.
output.jpg — Result of applying the style transfer.

**Requirements**
Python 3.7+
PyTorch
torchvision
matplotlib
pillow

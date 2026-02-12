# Single Pixel Coordinate Prediction

Predicting the (x,y) coordinates of a single white pixel in a 50×50 grayscale image using deep learning.

## What This Does

Takes an image with one white pixel and predicts where it is. Tested two approaches - a simple fully connected network and a CNN to see which works better.

## Quick Start

Open `pixel_prediction.ipynb` in Google Colab and run all cells. 

## Approach

- Generated 10k images with random pixel positions
- Tried FCN first (baseline)
- Then CNN (preserves spatial structure)
- CNN worked better and trained faster

## Requirements

Python 3.8+, PyTorch, NumPy, Matplotlib

Already installed if using Colab.

## Results

CNN converged in fewer epochs with better accuracy. Loss curves and prediction visualizations included in the notebook.

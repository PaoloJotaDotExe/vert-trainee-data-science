# MNIST Digit Recognition

**Notebook:** [`mnist_digits.ipynb`](mnist_digits.ipynb)

## Problem
Classify handwritten digits (0–9) from 28×28 grayscale images.

## Data
MNIST, loaded directly from `tensorflow.keras.datasets`.

## Approach
- Normalized pixel values and flattened/reshaped the images for the network.
- Built a `Sequential` neural network in Keras and trained it over several iterations.
- Tracked accuracy across experiments; it improved from ~82% in the first attempt to ~98%.

## Result
Test accuracy of **about 98%**.

---
*Group project from the Vert 2024 data trainee program. See the [main README](../README.md) for context.*

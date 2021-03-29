# Introduction
In this notebook, we will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Our completed pipeline will accept English text as input and return the French translation.

__Preprocess__ : Convert text to sequence of integers.

__Models__: Create models which accepts a sequence of integers as input and returns a probability distribution over possible translations.

__Prediction__: Run the model on English text.

# Setup

This project requires GPU acceleration to run efficiently. 

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

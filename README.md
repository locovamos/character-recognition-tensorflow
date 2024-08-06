# Character Recognition with TensorFlow

A simple project to build and train a neural network for recognizing handwritten digits using the MNIST dataset with TensorFlow and Keras.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy

Install the necessary libraries:
```bash
pip install tensorflow numpy
```

## Model Overview

- **Flatten Layer**: Converts each 28x28 image into a 1D vector.
- **Dense Layer**: 128 units with ReLU activation.
- **Dropout Layer**: 20% dropout rate.
- **Dense Layer**: 10 units with softmax activation.

## Training and Evaluation

- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Metrics**: Accuracy
- **Epochs**: 5

The model achieves approximately 97.8% accuracy on the test set.

# Multiclass Classification using MNIST Fashion Dataset

## Overview
This repository contains code and resources for training and evaluating a multiclass classification model using the MNIST fashion dataset. The goal is to classify images of fashion items into one of several categories such as T-shirts/tops, trousers, dresses, etc.

## Dataset
The MNIST fashion dataset consists of 60,000 training images and 10,000 test images across 10 categories. Each image is a 28x28 grayscale image associated with a label from 0 to 9, representing a specific fashion item category.

## Requirements
- Python 3.x
- Dependencies listed in `requirements.txt`. Install them using:
  ```
  pip install -r requirements.txt
  ```

## Files
- **`train.py`**: Script for training the classification model on the MNIST fashion dataset.
- **`evaluate.py`**: Script for evaluating the trained model on a test set.
- **`model.py`**: Defines the architecture of the neural network model.
- **`utils.py`**: Utility functions for data loading and preprocessing.
- **`requirements.txt`**: List of Python dependencies for the project.

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/mnist-fashion-classification.git
   cd mnist-fashion-classification
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model**:
   ```bash
   python train.py
   ```
   This will train a neural network model on the MNIST fashion dataset and save the trained model weights.

4. **Evaluate the model**:
   ```bash
   python evaluate.py
   ```
   This will evaluate the trained model on the test set and print evaluation metrics such as accuracy, precision, recall, and F1-score.

5. **Adjust model parameters**:
   Modify `model.py` to experiment with different neural network architectures, hyperparameters, or optimization algorithms.

## Acknowledgments
- The MNIST fashion dataset is publicly available and maintained by the Zalando Research team.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Author
- Moussa Moustapha
- Connect with me on Linkedin: [Moussa](https://www.linkedin.com/in/moussa-moustapha-moussa?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

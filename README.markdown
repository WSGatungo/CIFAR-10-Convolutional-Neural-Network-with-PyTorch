# CIFAR-10 CNN with PyTorch

This project implements a simple Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset using PyTorch. The CIFAR-10 dataset contains 60,000 32x32 color images across 10 classes (e.g., airplane, car, bird). The model achieves \~70% test accuracy after 10 epochs.

## Features

- Loads and preprocesses CIFAR-10 dataset using `torchvision`.
- Defines a simple CNN with two convolutional layers and two fully connected layers.
- Trains the model on a GPU (or CPU) with Adam optimizer and cross-entropy loss.
- Visualizes sample images and evaluates test accuracy.

## Requirements

- Kaggle Notebook Editor
- PyTorch
- Torchvision
- NumPy
- Matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:

   ```bash
   pip install torch torchvision numpy matplotlib
   ```

## Usage

1. Run the script in a Python environment (e.g., Jupyter Notebook, Kaggle, or locally):

   ```bash
   python cifar10_cnn.py
   ```
   - Alternatively, use a Kaggle notebook with GPU enabled for faster training.
2. The script will:
   - Download CIFAR-10 dataset.
   - Train the CNN for 10 epochs.
   - Display training loss and test accuracy (\~70%).
   - Optionally visualize sample images.

## Results

- Training loss decreases from \~1.35 to \~0.23 over 10 epochs.
- Test accuracy: \~70.47% on the CIFAR-10 test set.

## Recommendations

- Add data augmentation (e.g., random flips, crops) to improve accuracy.
- Experiment with deeper models or more epochs.
- Add dropout or batch normalization to reduce overfitting.
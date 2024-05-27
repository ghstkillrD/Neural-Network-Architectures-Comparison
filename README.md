# Neural Network Architectures Comparison

This repository contains code for loading, preprocessing, and training various neural network models using a dataset. The dataset is initially loaded as PyTorch tensors and then converted to NumPy arrays for use with TensorFlow/Keras. The primary goal of this project is to compare the performance of different neural network architectures and to observe the effects of different hyperparameters, such as learning rates, on model performance.

- **Dataset** - https://klnaclk-my.sharepoint.com/:f:/g/personal/ranathu-cs19060_stu_kln_ac_lk/EjPs0JrZAgxMoYIx8v_GP0YBsYJQM1e2ZlGeu4G9L_J19Q

## Features

- Load and preprocess data from PyTorch tensors.
- Define and compare different neural network architectures:
  - Basic Simple Neural Network
  - Basic Convolutional Neural Network
  - Improved Simple Neural Network
  - Improved Convolutional Neural Network
- Train and evaluate models using TensorFlow/Keras.
- Experiment with different learning rates.

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow
- PyTorch
- scikit-learn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/NeuralNetworkArchitecturesComparison.git
    cd NeuralNetworkArchitecturesComparison
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
    
### Usage

1. Load your dataset into PyTorch tensors and save them as `.pt` files.
2. Modify the code to load your specific dataset.
3. Run the script to train and evaluate different neural network models.
    ```bash
    python train_models.py
    ```
    
### Experimenting with Learning Rates

- Adjust the `learning_rates` list in the script to test different learning rates and observe their effects on model performance.

## Results

- The script outputs the test loss and accuracy for each neural network model.
- Training histories are recorded for further analysis and visualization.

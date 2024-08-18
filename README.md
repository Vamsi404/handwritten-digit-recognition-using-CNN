# 🖥️ MNIST CNN Classifier

This repository contains a Convolutional Neural Network (CNN) built with Keras for classifying handwritten digits from the MNIST dataset. The model achieves high accuracy using three convolutional layers and fully connected dense layers for multi-class classification.

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Project Overview

This project implements a CNN to classify handwritten digits (0-9) using the MNIST dataset. The model achieves an accuracy of 99% on the test dataset, demonstrating effective learning and classification performance.

## 🧠 Model Architecture

The model uses the following architecture:

1. **Input Layer**: 28x28 grayscale images.
2. **Convolutional Layer 1**: 32 filters, 3x3 kernel, ReLU activation.
3. **Max-Pooling Layer 1**: 2x2 pool size.
4. **Convolutional Layer 2**: 64 filters, 3x3 kernel, ReLU activation.
5. **Max-Pooling Layer 2**: 2x2 pool size.
6. **Convolutional Layer 3**: 64 filters, 3x3 kernel, ReLU activation.
7. **Flatten Layer**: Converts the 3D feature maps into 1D.
8. **Dense Layer 1**: 64 units, ReLU activation.
9. **Output Layer**: 10 units, Softmax activation.

## ⚙️ Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/mnist-cnn-classifier.git
    ```
2. Navigate to the project directory:
    ```bash
    cd mnist-cnn-classifier
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 📝 Usage

1. Run the script to train the model:
    ```bash
    python mnist_cnn.py
    ```
2. The training and validation progress will be displayed. The model will be trained for 5 epochs with a batch size of 128.

3. After training, the model's accuracy and loss will be evaluated on the test dataset.

## 📊 Results

- **Training Accuracy**: ~99.18%
- **Validation Accuracy**: ~98.87%
- **Test Accuracy**: 99.00%

## 📂 Directory Structure

```
mnist-cnn-classifier/
│
├── mnist_cnn.py            # Main Python script
├── requirements.txt        # List of required packages
├── README.md               # Project documentation
└── models/                 # Directory to save the trained model
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Vamsi404/handwritten-digit-recognition-using-CNN/issues).

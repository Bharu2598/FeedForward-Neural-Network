# FeedForward-Neural-Network

## Overview
This repository contains a Python implementation of a **Feedforward Neural Network (FNN)** for classifying banknotes as either genuine or counterfeit. The model is built using **TensorFlow/Keras** and trained on a dataset containing numerical features extracted from banknotes.

## Dataset
The dataset consists of banknote features and their corresponding class labels:
- **Variance of Wavelet Transformed Image**
- **Skewness of Wavelet Transformed Image**
- **Kurtosis of Wavelet Transformed Image**
- **Entropy of Image**
- **Class Label (0 = Genuine, 1 = Counterfeit)**

### Download Dataset
Kindly download the **banknote_Authentication.csv** file from the attachments and place it in the same directory as the script.

## Installation
Ensure you have Python installed, and install the necessary libraries using:

```bash
pip install pandas numpy tensorflow scikit-learn
```

## Implementation
The script performs the following steps:
1. **Load the dataset** from `banknote.csv`.
2. **Preprocess the data** by splitting into training and testing sets and normalizing features.
3. **Build the Feedforward Neural Network** using TensorFlow/Keras.
4. **Train the model** with backpropagation and optimization.
5. **Evaluate model performance** on the test set.
6. **Make predictions** on new data.

## Running the Script
To train and evaluate the model, run the following command:

```bash
python FeedForwardTechnique.py
```

## Model Architecture
The neural network consists of:
- **Input Layer:** Accepts numerical banknote features.
- **Hidden Layers:** Two fully connected layers with ReLU activation.
- **Output Layer:** Single neuron with Sigmoid activation for binary classification.

## Results
After training for **50 epochs**, the model achieves high accuracy on the test set.

## Contributing
Feel free to contribute by improving the model, adding more features, or using different architectures!

## License
This project is licensed under the MIT License.

## Contact
For any queries, please open an issue or reach out via GitHub.


# Fashion MNIST Neural Network with Precision and Recall Metrics

This project builds a neural network in NumPy to classify Fashion MNIST images. It measures not only accuracy but also precision and recall to better understand model performance.

## Features

- Two hidden layers with 300 neurons
- He initialization
- ReLU and Softmax activations
- Mini-batch gradient descent
- Precision and recall calculation per batch
- Saves best weights based on test accuracy

## Metrics

- **Accuracy:** Overall percentage of correct predictions
- **Precision:** How many predicted positives were true positives
- **Recall:** How many true positives were recovered
- **Cross-Entropy Loss:** Training objective

## Requirements

- Python 3
- NumPy
- Pandas
- scikit-learn
- Matplotlib

## How to Run

1. Download `fashion-mnist_train.csv`
2. Install dependencies
3. Run the script
4. Monitor logs for accuracy, precision, recall

## License

MIT License

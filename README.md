# Simple MNIST Neural Network from Scratch

This repository contains Python code for building a simple two-layer neural network from scratch and training it on the MNIST handwritten digit dataset. The code is implemented using basic Python and NumPy, without relying on deep learning frameworks like TensorFlow or PyTorch.

## Features
- **Data Preprocessing:** The MNIST dataset is loaded from a CSV file and preprocessed to prepare it for training.
- **Forward Propagation:** Forward propagation is performed to compute the activations of each layer in the neural network.
- **Backpropagation:** Backpropagation is used to compute the gradients of the loss function with respect to the parameters of the network.
- **Gradient Descent:** Gradient descent is employed to update the parameters of the network and minimize the loss function.
- **Testing and Evaluation:** The trained model is tested on a validation set, and accuracy is calculated to evaluate its performance.

## Usage
1. Clone the repository: `git clone https://github.com/OmBaval/Neural-Network-from-scratch-without-TensorFlow-PyTorch.git`
2. Navigate to the repository: `cd simple-mnist-nn`
3. Run the Python script: `python mnist_nn.py`

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
This code is based on a tutorial on building neural networks from scratch and is intended for educational purposes. Credit goes to the original author for providing valuable insights into the implementation of neural networks.

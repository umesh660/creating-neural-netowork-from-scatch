# creating-neural-netowork-from-scatch

This Python script demonstrates a simple implementation of a two-layer neural network trained on the MNIST handwritten digit dataset.

## Dataset

The MNIST dataset contains:
- Images of handwritten digits (0–9)
- Each image is represented as a 784-dimensional vector (28x28 pixels flattened)
- Includes a 'label' column specifying the digit for each image

## Network Architecture

- **Input Layer (a[0])**: 784 units
- **Hidden Layer (a[1])**: 10 units with ReLU activation
- **Output Layer (a[2])**: 10 units with softmax activation

## Implementation Details

### Libraries Used

- `numpy` for numerical operations
- `pandas` for data handling
- `matplotlib` for visualization

### Files

- `train.csv`: CSV file containing the MNIST dataset

### Code Structure

1. **Data Preparation**:
   - Reads and preprocesses the dataset (shuffling and normalization)

2. **Parameter Initialization**:
   - Random initialization of network parameters (weights and biases)

3. **Forward Propagation**:
   - Computes activations through the network layers
   - Activation Functions:
     - ReLU for hidden layer
     - Softmax for output layer

4. **Backward Propagation**:
   - Computes gradients of the loss function with respect to network parameters

5. **Gradient Descent**:
   - Optimizes parameters using batch gradient descent

6. **Evaluation**:
   - Computes accuracy metrics during training


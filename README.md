# Simple neural-networks-algorithm
This project demonstrates the implementation of a simple neural network to solve the XOR problem using Python and TensorFlow/Keras. The XOR function is a classic example of a binary classification problem where the output is 1 if the two inputs are different and 0 otherwise.
### Requirements
1. Python 3.8+
2. TensorFlow 2.x
3. NumPy
## How It Works
1. Input Data:
The input (x_train) consists of all possible combinations of two binary values [0, 0], [0, 1], [1, 0], [1, 1].
The output (y_train) corresponds to the XOR of the two inputs.

2. Neural Network Architecture:
Input Layer: Accepts two input features.
Hidden Layer: Contains 4 neurons with ReLU activation.
Output Layer: Contains 1 neuron with a sigmoid activation for binary classification.

3. Training:
The network is trained using the Adam optimizer and binary cross-entropy as the loss function for 100 epochs.

4. Output:
After training, the model predicts the XOR output for the given inputs and evaluates the training accuracy.

# Fashion-MNIST Image Classification with TensorFlow
---

This project demonstrates how to build a simple image classification model using TensorFlow and the Fashion-MNIST dataset. The Fashion-MNIST dataset consists of 70,000 grayscale images of 10 different types of clothing, with 7,000 images per class.

The code is written in Python and uses the TensorFlow and Keras libraries for building and training the model. The model architecture consists of a single hidden layer with 128 neurons and ReLU activation, followed by a 10-neuron output layer with softmax activation. The model is trained using the sparse categorical cross-entropy loss function and the Adam optimizer.

### Requirements
---

- Python 3.6 or higher
- TensorFlow 2.0 or higher
- NumPy
- Matplotlib

### Usage
---

To run the code, simply run `pip install tensorflow numpy matplotlib` then run `fashion_mnist.py` file in a Python environment that meets the requirements listed above. The script will download the Fashion-MNIST dataset and split it into training and testing sets, normalize the pixel values to the range [0, 1], build and train the model, and evaluate the model on the test set.

### Results
---

After training the model for 10 epochs, the test accuracy achieved is around 87%, which is a decent result for such a simple model, You could also increase the epochs to get better prediction. The results may vary slightly each time the script is run due to the random initialization of the weights.
MNIST Digit Recognition (From Scratch)
This project implements a Neural Network for digit classification using the MNIST dataset, created from scratch using NumPy. The goal is to classify handwritten digits (0-9) based on pixel data from images in the MNIST dataset.

 - Project Overview
This is a simple, yet powerful 2-layer Neural Network built from the ground up using basic linear algebra and backpropagation. The model achieves an accuracy of around 85% on the MNIST dataset, which can be further improved with hyperparameter tuning and more advanced techniques.

 - Tech Stack used
- Python 
- Numpy
- Matplotlib
- Jupyter Notebook
- MNIST Dataset
  
 - Model Architecture
Input Layer: 784 neurons (representing 28x28 pixels of the image)

Hidden Layer: 10 neurons (arbitrary number chosen for simplicity)

Output Layer: 10 neurons (representing digits 0-9)

Activation Functions:
ReLU (Rectified Linear Unit) for hidden layer

Softmax for output layer

 - How It Works
Forward Propagation: Data passes through the network, layer by layer, and activations are calculated.

Backpropagation: Gradients of the loss function are calculated to update the model’s parameters using the gradient descent algorithm.

Training: The model is trained using the MNIST dataset to minimize the loss and increase prediction accuracy.

 - Sample Output
Here’s an example of the network making predictions:

Prediction: 7

Label: 7

Image:

You can see how the model recognizes handwritten digits and classifies them based on the input image.

 - Technologies Used
Python – Programming language used for development.

NumPy – For implementing neural network functions like matrix multiplication, forward propagation, and backpropagation.

Matplotlib – For visualizing the dataset and predictions.

Kaggle – The platform used to run and test the model.
 - How to Run
You can run the code either in Kaggle or locally.

Option 1: Run on Kaggle
Go to the Kaggle Notebook and open the notebook.

Run all cells in order to see the model's training process and predictions.

Clone this repository:
git clone https://github.com/your-username/Building-a-NN-on-MNIST-Dataset-Using-NumPy.git
cd Building-a-NN-on-MNIST-Dataset-Using-NumPy

Launch Jupyter Notebook:
jupyter notebook

 - Author
Name: Sam
GitHub: https://github.com/TravisKalanick
LinkedIn: https://www.linkedin.com/in/samardeep-singh-488b4024b/

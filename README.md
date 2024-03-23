# Mnist Handwritten Digits Detection 🔢

## Type of problem : Multiclass  Classification problem 

## Dataset Description:

- MNIST Dataset: The MNIST dataset is a widely used benchmark dataset in the field of machine learning and computer vision. It stands for "Modified National Institute of Standards and Technology" and is composed of a large collection of handwritten digits. 

### Description: 

- Size: The MNIST dataset contains 70,000 grayscale images of handwritten digits.

- Labels: Each image is associated with a label from 0 to 9, indicating the digit that the image represents. This makes MNIST a classification dataset, where the task is to classify the images into one of the ten digit classes.

- Purpose: classify the images into one of the ten digit classes.

## The proposed framework is summarized in the following steps:

1- Import Libraries: Import the necessary libraries, typically TensorFlow or Keras in Python.

2- Data exploration & visualization 🔎 : visualise a subset of data by imshow function.

3- Data preprocessing 🛠 :
- Normalization: Normalize the pixel values of the images to be in the range [0, 1]. This helps in stabilizing the training process and improving convergence.

- Reshaping: Reshape the input images to the required format expected by the deep learning model. For MNIST, this typically involves adding a channel dimension to represent grayscale images.

- One-Hot Encoding : you need to one-hot encode the class labels.

4- Model Architecture is (LeNet-5) .

5- Compiles the model : with Adam Optimizer, sparse categorical crossentropy loss, and accuracy metric.

6- Trains the model on the training data for 10 epochs with a batch size of 128.

7- Evaluates the trained model on the test data and prints the test accuracy.

8- Saving model 🗃.

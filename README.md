# Dog-vs-Cat-Image-Recognition-using-CNN
# Project overview:
This project implements a Convolutional Neural Network (CNN) for classifying images of cats and dogs. The dataset used contains 12,500 images for each class. The model achieved an accuracy of 83.36% after training for 20 epochs. The goal of this project is to demonstrate the power of CNNs in solving image classification problems.

# Dataset
The dataset contains 12,500 images each for cats and dogs, making a total of 25,000 images. It is taken from Kaggle.
I am providing the link of my google drive for the dataset: 

# Tech
- Python
- Tensorflow
- Keras

# Model Architecture

1️⃣ Four Convolutional layers followed by MaxPooling Layers:
▪️The convolutional layer is for detecting features in the input images
▪️The MaxPooling layer reduces the spatial dimensions by selecting the maximum value from each patch

2️⃣ Flattening layer:
▪️Flatten the output of the convolutional layer into a 1D vector for fully connected layer

3️⃣ Fully Connected Layer:
▪️Three fully connected layers are added followed by the output of the flattened layer
▪️Batch Normalization and Dropout are also added to enable fast and stable training along with avoiding overfitting of the model

5️⃣ Final Layer:
▪️The final layer is the output layer which has the activation function sigmoid to classify the results into two classes: Cat or Dog

# Results
The testing accuracy of this model is 83.36%.



### CNN - Classifying Dogs Vs Cats Images

## Project Overview
* This project implements a Convolutional Neural Network (CNN) using TensorFlow & Keras to classify images of cats and dogs.
* The model is trained on the Kaggle Dogs vs. Cats dataset and achieves accuracy in distinguishing between the two classes.
Data set Contains 2000 images (1k cats, 1k dogs)

## Technologies Used
* Backend: Python
* Data Handling: Pandas for model building
* Neural Network: CNN for Image classification

## Features
* Used ImageDataGenerator to produce batches of enhanced images
* Preprocesses images (resizing, normalization)
* Builds a CNN architecture with sequential model having Conv2D, MaxPooling, Flatten and Dense layers
* Uses ReLU activation for hidden layers and Sigmoid for classification
* Trains using Adam optimizer & Binary Crossentropy loss
* Evaluates model performance using accuracy and loss curves
* loads the trained model for future predictions
* Classifies the image given as dog or cat



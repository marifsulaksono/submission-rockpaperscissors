# Rock-Paper-Scissors Image Classification
This project is a submission for the Dicoding Machine Learning class. It focuses on creating a classifier to distinguish between hand gestures of rock, paper, and scissors using a Convolutional Neural Network (CNN).

## Project Overview
The goal is to build an image classification model capable of recognizing hand gestures (rock, paper, scissors). The dataset is split into 60% training and 40% validation images.

## Dataset
The dataset contains images from three classes:

- Rock: 726 images
- Paper: 712 images
- Scissors: 750 images
<br />The data is augmented to improve model generalization with techniques like rotation, horizontal flipping, and shearing.

## Model Architecture
The model is a CNN built with:

- Multiple convolutional layers to extract features.
- Dense layers for classification with a softmax activation for the three gesture classes.

## Training
- The model is trained for 20 epochs with early stopping when accuracy reaches 98%.
- Optimizer: Adam
- Loss function: Categorical Crossentropy
- Image augmentation techniques: Rotation, horizontal flip, and shearing.

### Confusion Matrix & Classification Report
The confusion matrix and classification report provide insight into the model’s performance. The model struggles to classify gestures with high precision but performs uniformly across all classes.

## How to Run
1. Download the dataset from the provided link.
2. Train the model using TensorFlow and Keras.
3. Evaluate the model using the validation set and visualize the confusion matrix.
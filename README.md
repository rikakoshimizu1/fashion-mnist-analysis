# Fashion MNIST Feedforward Neural Network

## Overview
This project explores the fundamentals of **deep learning** by designing, training, and evaluating feedforward neural networks using the `Fashion MNIST` dataset. The goal is to understand how neural networks perform **image classification** tasks and to experiment with various **hyperparameters and regularization methods** to improve model accuracy.

## Objective
To apply deep learning techniques to classify **grayscale images** of clothing items from the `Fashion MNIST` dataset. The assignment involves building feedforward neural networks, tuning hyperparameters, implementing regularization and normalization, and analyzing the model's performance. 

## Dataset
The **Fashion MNIST** dataset contains 70,000 grayscale images of size 28x28 pixels, divided into:
 - Training set: `60,000` images
 - Test set: `10,000` images

Each image represents one of **10 fashion item categories**:
 - **0**: T-shirt/top
 - **1**: Trouser
 - **2**: Pullover
 - **3**: Dress
 - **4**: Coat
 - **5**: Sandal
 - **6**: Shirt
 - **7**: Sneaker
 - **8**: Bag
 - **9**: Ankle Boot

## Features
 - **Model Architecture**: Construction of **feedforward neural networks** with hidden layers and activation functions (`ReLU`, `softmax`).
 - **Hyperparameter Tuning**: Adjusting **learning rate**, **batch size**, and **epochs** to improve accuracy.
 - **Regularization**: Applying `dropout` to reduce overfitting.
 - **Normalization**: Using `batch normalization` to stabilize and accelerate training.
 - **Visualization**: Displaying class distributions, training/validation accuracy, and prediction results with `matplotlib`. 

## Challenges
 - Determining the best hyperparameters for the feedforward neural network was initially difficult without a systematic approach.
 - Managing model overfitting required experimenting with regularization techniques like `dropout`.
 - Improving model performance on the Fashion MNIST dataset involved trial and error before applying hyperparameter tuning methods such as `GridSearchCV`.
 - Balancing training time and accuracy was a challenge when adjusting batch size and number of epochs. 

## Analysis and Insights
This assignment highlighted the critical role of **hyperparameter tuning** in optimizing model performance. While it was challenging to intuitively determine the best ways to improve the neural network, applying systematic hyperparameter tuning allowed identification of the most effective parameters to enhance accuracy. The process demonstrated how automated search methods, such as `GridSearchCV`, could be valuable tools for efficiently exploring combinations of hyperparameters. Using these optimized parameters resulted in improved test accuracy and a more robust model overall. 

## About 
This Jupyter Notebook was completed as part of the **UCSC Silicon Valley Extension Deep Learning and Artificial Intelligence** program.

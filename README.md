# Convolutional_Neural_Network_MNIST
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9), and the goal is to train a model that can accurately predict the digit in each image.

This tutorial is designed to provide a comprehensive guide to convolutional projects for the Data Analysis course at IIT Hyderabad, where I worked as a teaching assistant. The tutorial covers the basics of convolutional operations, including  data preparation,  custom model creation, training evaluation, applying k-fold cross-validation, and visualizing the layers between the convolutional layers.

## Dataset
The MNIST dataset is included in the Keras library and can be loaded using the keras.datasets.mnist module. It contains 60,000 training images and 10,000 test images.
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/ac0c94a8-f200-4761-9a81-f8dd26f4c638)

## Model Architecture
The CNN model architecture consists of multiple convolutional layers followed by max-pooling layers to extract features from the input images. The extracted features are then flattened and passed through fully connected layers to perform classification.
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/543cfa42-a3a5-4767-b9bf-d6036909f7db)

## Training
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/21db3670-b824-42f9-8d6d-0a1001364571)

## Visualize outputs of some Conv2D layers for a random image
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/ddc66710-53f7-42c8-9b4d-0e9b2e12df4d)


## K-Fold Cross-validation 

![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/d9b75449-b354-4ec3-b0cf-e62647bc6f5f)
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/fbc74c24-205f-4fad-83e4-13bd8d0e91ae)


## Evaluation
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/26ea2712-c5e8-41e9-806d-5ff2afc059ca)
## Results
![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/b0f2d343-9269-4ed0-bf63-186bdd8eebdd)

![image](https://github.com/AshishKumarSingh03/Convolutional_Neural_Network_MNIST/assets/116654089/431561c6-bb4e-4669-b614-ccc629eff967)





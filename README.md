# Image-Classification-using-CNN-ANN-
The CIFAR-10 dataset is used, which comprises 60,000 32x32 color images in 10 different classes, split into 50,000 training images and 10,000 testing images. Initially, the dataset is loaded and explored to understand its structure, followed by displaying a sample image to verify the data's correctness. The dataset labels are reshaped for easier processing, and a function is created to visualize the images with their corresponding class labels. 

To improve the model's input data quality, the pixel values of the images are normalized by dividing by 255, ensuring they range between 0 and 1. 

Two different neural network architectures are then constructed and compared: an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN). The ANN is trained for 5 epochs, achieving an accuracy of approximately 49.76% on the training data. The CNN includes convolutional layers, activation functions (ReLU), max pooling layers, and dense layers. It is trained for 10 epochs, showing a significant improvement with an accuracy of approximately 74.58% on the training data. 

Finally, the models are evaluated on the test dataset and their Classification Reports are printed, showing the CNN Model signifcantly outperforming the ANN Model.

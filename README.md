# Face-Mask-Detection

During pandemic COVID-19, WHO has made wearing masks compulsory to protect against this deadly virus. In this repo we will develop a machine learning project – Real-time Face Mask Detector with Python.

## About the Project
In this project, we have developed a deep learning model for face mask detection using Python, Keras, and OpenCV. We developed the face mask detector model for detecting whether person is wearing a mask or not. We have trained the model using Keras with network architecture. Training the model is the first part of this project and testing using webcam using OpenCV is the second part.

## Dataset
The dataset we are working on consists of 1376 images with 690 images containing images of people wearing masks and 686 images with people without masks.
#### with mask
![](https://github.com/ramkiran55/Face-Mask-Detection/blob/main/Img/dataset-with-mask.png)
#### without mask
![](https://github.com/ramkiran55/Face-Mask-Detection/blob/main/Img/dataset-without-mask.png)

## Steps: 
#### 1. Build the neural network:
Import all the libraries and modules required.
This convolution network consists of two pairs of Conv and MaxPool layers to extract features from the dataset. Which is then followed by a Flatten and Dropout layer to convert the data in 1D and ensure overfitting.
And then two Dense layers for classification.
#### 2. Image Data Generation/Augmentation:
Using Train data to train the model and Test data for validation
#### 3. Initialize a callback checkpoint to keep saving best model after each epoch while training:
#### 4. Train the model:
Now we will test the results of face mask detector model using OpenCV.
Run the project and observe the model performance.

## Outputs:
![](https://github.com/ramkiran55/Face-Mask-Detection/blob/main/Outputs/Screenshot%20(779).png)

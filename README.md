
# Male & Female Classification with Convolutional Neural Network 👨👩

## Overview 📋

This project focuses on classifying images of males and females using a Convolutional Neural Network (CNN). The goal is to achieve high accuracy in gender classification through deep learning techniques. The dataset used includes a diverse set of images to ensure robust and generalizable model performance.

## Table of Contents 📚

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [How To Run](#howtorun)
- [Results](#results)

## Introduction 🚀

- Male & Female Classification is a deep learning project that uses a Convolutional Neural Network to automatically classify images based on gender.
-  This project can be utilized in various applications such as social media analytics, security systems, and more.

## Dataset 📦

- The dataset consists of images labeled as either male or female.
- These images are split into training and test sets to facilitate model training and evaluation. 

## Model Architecture 🧠

The CNN model is constructed using TensorFlow/Keras and includes the following layers:
- Convolutional layers with ReLU activation
- Max Pooling layers
- Dropout layers for regularization
- Fully connected (Dense) layers
- Softmax activation in the final layer for binary classification

## Training 🎯

The model is trained with the following parameters:
- **Optimizer**: Adam
- **Loss Function**: sparse_categorical_crossentropy
- **Batch Size**: 32
- **Epochs**: 5



## Evaluation 📊

- The model's performance is evaluated using accuracy, precision, recall, and F1-score.
![Screenshot (27)](https://github.com/AabshaarShaikh20/Male-And-Female-Classification-CNN-Project/assets/169930813/7043a62f-1863-416e-9aa7-48b924bbd4d9)


## How to Run 🛠️

To run this project locally, follow these steps:

1. Download the .ipynb file for the main code file and the zip file for the dataset
2. Install the required libraries and packages
3. Change all the file path and you are ready to run :)


## Results 📈

The model achieves an accuracy of **94%** on the validation set. Below are some sample results:

![Screenshot (28)](https://github.com/AabshaarShaikh20/Male-And-Female-Classification-CNN-Project/assets/169930813/c825a6e9-bbee-455c-a5df-79635918b3ca)


![Screenshot (29)](https://github.com/AabshaarShaikh20/Male-And-Female-Classification-CNN-Project/assets/169930813/19edafbd-bd9f-4de1-a538-628b992a96db)




## Authors

- [@AabshaarShaikh](https://github.com/AabshaarShaikh20)
- aabshaarshaikh@gmail.com

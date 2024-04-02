# Face Mask Detection
This repository contains code for training and deploying deep learning models (CNN, VGG16, and Inception) to detect the presence of face masks in images. The dataset consists of two folders: "with_mask" containing images of people wearing masks and "without_mask" containing images of people without masks.

Dataset link:https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

Objectives
Develop and compare multiple deep learning models (CNN, VGG16, Inception) for accurately detecting the presence of face masks in images.
Train the models on a dataset of labeled images containing people with and without masks to achieve high accuracy.
Evaluate the performance of each model to determine their effectiveness in face mask detection.
Then train models to classify whether an input image contains a person with or without a mask.

Process
Data Preparation: Organize the dataset into two folders: "with_mask" containing images of people wearing masks and "without_mask" containing images of people without masks.

Model Training:Train a Convolutional Neural Network (CNN) model to learn features and patterns from the image data. Achieve 92% accuracy on the test set.
Utilize the VGG16 architecture to train another model on the same dataset, achieving 50% accuracy on the test set.
Train an Inception model to capture more complex features, achieving 77% accuracy on the test set

Model Evaluation: Evaluate the performance of each trained model using metrics such as accuracy, precision, recall, and F1-score. Analyze the strengths and weaknesses of each model in face mask detection.

Results: Train models and then provide option upload images and obtain predictions regarding the presence of face masks.

Dependencies
Python,
TensorFlow,
Keras,
fine tuning,
Google colab

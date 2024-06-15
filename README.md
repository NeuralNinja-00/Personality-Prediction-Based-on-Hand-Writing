# Personality-Prediction-Based-on-Hand-Writing
**Overview**

This project aims to predict personality traits from handwriting samples using deep learning techniques. The model is trained to classify handwriting images into one of the five major personality traits: Agreeableness, Conscientiousness, Extraversion, Neuroticism, and Openness. The dataset consists of images categorized into folders corresponding to these traits.

**Objectives**

Data Collection: Organize handwriting images into training and testing datasets, each containing subfolders for the five personality traits.

Data Preprocessing: Read and preprocess images to ensure uniformity in size and pixel value normalization.

Feature Extraction and Model Training: Use Convolutional Neural Networks (CNNs) to extract features from the handwriting images and train a classification model.

Evaluation and Prediction: Evaluate the model's performance on the test set and use it to predict personality traits from new handwriting samples.

**Methodology**

Data Preprocessing:
Images are resized to a uniform size (128x128 pixels) and normalized.
Labels are assigned based on the folder names.

Model Architecture:
A simple CNN architecture is used, consisting of convolutional layers for feature extraction, followed by dense layers for classification.

Training:
The model is trained using the training dataset with a categorical cross-entropy loss function and Adam optimizer.
Validation is performed on the test dataset to monitor performance.

Evaluation:
Model accuracy is measured on the test set.
Predictions are made on new handwriting samples to demonstrate the model's capabilities.

Tools and Technologies:
Programming Language: Python
Libraries: TensorFlow, Keras, OpenCV, NumPy, pandas, scikit-learn
Environment: Jupyter Notebook 

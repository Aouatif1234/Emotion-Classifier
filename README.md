# Emotion-Classifier
Emotion Classifier Using Texture Features and SVM

This repository contains an emotion classifier that uses texture features and a Support Vector Machine (SVM) model to classify facial expressions into one of the seven emotions: happiness, neutral, sadness, anger, surprise, disgust, and fear.


# Introduction
The project focuses on classifying facial expressions into different emotion categories using texture features extracted with the Gray-Level Co-Occurrence Matrix (GLCM) and a Support Vector Machine (SVM) classifier. The objective is to improve human-computer interaction by enabling systems to understand and respond to human emotions.

The script will load the images, extract the features, train the SVM model, and output the classification accuracy and confusion matrix.

# Dataset
The dataset used in this project is the Emotion classifier FER dataset from Kaggle. This dataset contains labeled facial images for various emotions, including:

angry: Contains images labeled as "angry"

disgusted: Contains images labeled as "disgusted"

fearful: Contains images labeled as "fearful"

happy: Contains images labeled as "happy"

neutral: Contains images labeled as "neutral"

sad: Contains images labeled as "sad"

surprised: Contains images labeled as "surprised"

Please update the path variables in the code to point to your dataset folders.

# Features Extraction
The emotion classification is based on texture analysis using the Gray-Level Co-Occurrence Matrix (GLCM). For each image, we calculate the following texture features:

Contrast

Correlation

Energy

Homogeneity

These features are then normalized and used to build the feature vectors for classification.

# Model
The classifier uses an SVM with a linear kernel for training. SVMs are effective in high-dimensional spaces and are widely used for classification problems due to their ability to handle non-linear relationships.

# Installation
To run the project, you'll need to install the following dependencies:

pip install numpy

pip install opencv-python

pip install scikit-image

pip install matplotlib

pip install scikit-learn ' 



# Results
The classifier outputs the following results:

Prediction of emotions: The predicted emotion labels for the test set.

Accuracy of SVM: The accuracy score of the SVM model on the test set.

Confusion Matrix: The confusion matrix showing the performance of the classification for each emotion.

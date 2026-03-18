Machine-Learning-Internship-Tasks-Skillcraft-Technology
This repository contains multiple Machine Learning projects developed using Python and Jupyter Notebook. Each project focuses on a different ML technique and demonstrates the complete workflow, including data preprocessing, visualization, model building, and evaluation.

These projects are suitable for learning, practice, and portfolio purposes.

Project Files Description

SCT_ML_1 – House Price Prediction
This project focuses on predicting house prices using supervised learning (regression) techniques.

Key Concepts Covered:

Understanding and exploring the housing dataset

Handling missing values and feature selection

Data preprocessing and normalization

Building regression models to predict house prices

Evaluating model performance using appropriate metrics

Outcome: The model learns the relationship between various house features (such as size, location-related factors, etc.) and predicts the expected house price.

SCT_ML_2 – Mall Customer Dataset Analysis
This project performs customer segmentation using unsupervised learning techniques.

Key Concepts Covered:

Exploratory Data Analysis (EDA) on customer data

Visualization of customer behavior patterns

Feature selection for clustering

Applying clustering algorithms (such as K-Means)

Interpreting clusters to understand different customer groups

Outcome: Customers are grouped into meaningful segments based on their spending behavior and income, helping businesses understand and target different customer types effectively.

SCT_ML_3 – Support Vector Machine (SVM) Classification
This project demonstrates the implementation of Support Vector Machine (SVM) for classification tasks.

Key Concepts Covered:

Introduction to SVM and margin-based classification

Data preprocessing and feature scaling

Training an SVM classifier

Hyperparameter tuning (kernel selection, C, gamma)

Model evaluation using accuracy and classification metrics

Outcome: The SVM model successfully classifies data points into different classes with optimized decision boundaries.

Technologies and Libraries Used

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Purpose of the Repository

The main goal of this repository is to strengthen machine learning fundamentals and gain hands-on experience with real-world datasets. These projects can be used for academic submissions, internships, or as part of a personal ML portfolio.

SCT_ML_4 - Developed a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems. Project: Hand Gesture Recognition Using CNN
Objective:

Recognize and classify hand gestures from images or live video.

It can be used for gesture-controlled applications, e.g., sign language recognition or touchless interfaces.

Dataset:

LeapGestRecog dataset from Kaggle

10 gesture classes: c, down, fist, fist_moved, index, l, ok, palm, palm_moved, thumb

~20,000 images, split 80% training / 20% validation

Technology Stack:

Python & Google Colab

Kaggle API – download dataset

TensorFlow & Keras – build/train CNN

OpenCV – capture webcam input and predict gestures in real-time

CNN Architecture: 3 Conv2D + MaxPooling layers → Flatten → Dense layers → Output softmax for 10 classes

Workflow:

Download dataset and reorganize images

Preprocess images (resize, normalize)

Build and train CNN

Save model (.h5 and .keras)

Use webcam or uploaded images for real-time gesture prediction

Outcome:

High accuracy on validation (~99.98%)

Real-time prediction works via webcam or static image upload

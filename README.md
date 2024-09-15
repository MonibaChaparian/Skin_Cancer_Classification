Skin Cancer Classification using Deep Learning :

This project demonstrates a deep learning approach to skin cancer classification using the HAM10000 dataset. The model achieves high performance with an accuracy of 98%, leveraging Convolutional Neural Networks (CNNs) to classify images into various skin lesion categories.

Key Features:

Data Handling:
Downloads and preprocesses the HAM10000 dataset.
Applies oversampling to address class imbalance.
Utilizes data augmentation to enhance model robustness.
Model Architecture:

Convolutional Neural Network (CNN) with four convolutional blocks and an artificial neural network block.
Employs Conv2D layers with MaxPool2D for feature extraction and Dense layers for classification.
Training and Evaluation:

Trained on augmented data with a custom learning rate schedule.
Evaluated using accuracy, confusion matrix, and classification report.
Visualization:

Displays confusion matrix and classification report for model performance.
Includes sample predictions and model performance plots.
Performance:
Accuracy: 98%
Confusion Matrix: Visualizes the classification results across different skin lesion types.
Classification Report: Provides precision, recall, and F1-score metrics for each class.
Data:
Dataset: HAM10000 skin lesion images, preprocessed and augmented.
This project serves as a robust example of applying deep learning techniques to medical image classification, with a focus on improving accuracy and handling imbalanced datasets.

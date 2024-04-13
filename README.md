# Architectural Style Classification using SVM

## Overview
This project aims to classify architectural styles, specifically Russian Revival and American Foursquare, using Support Vector Machine (SVM) classifiers. Various feature extraction techniques such as Scale-Invariant Feature Transform (SIFT), Histogram of Oriented Gradients (HOG), Hu Moments, and Local Binary Patterns (LBP) are employed to extract discriminative features from the images.

## Dataset
The dataset consists of images of Russian Revival and American Foursquare architectural styles. These images are organized into two directories, one for each architectural style. The dataset can be downloaded from [Kaggle] (https://www.kaggle.com/datasets/dumitrux/architectural-styles-dataset) or any other source.

## Feature Extraction
1. **SIFT (Scale-Invariant Feature Transform)**: Detects keypoints and computes SIFT descriptors for each image.
2. **HOG (Histogram of Oriented Gradients)**: Calculates HOG features to represent the local shape and structure of an image.
3. **Hu Moments**: Computes Hu Moments to capture shape information.
4. **LBP (Local Binary Patterns)**: Extracts LBP features to describe texture information.

## SVM Classification
1. Split the dataset into training and testing sets.
2. Train SVM classifiers using different feature sets: SIFT, HOG, Hu Moments, and LBP.
3. Evaluate the classifiers using accuracy and generate classification reports to assess precision, recall, and F1-score for each class.

## Results
- HOG features achieved the highest accuracy of around 96.5%.
- SIFT and Hu Moments features achieved accuracy around 68.5% and 64.3%, respectively.
- LBP features achieved an accuracy of around 64.3%.

## Conclusion
This project demonstrates a comprehensive approach to architectural style classification using SVM classifiers with various feature extraction techniques. The results highlight the effectiveness of HOG features in distinguishing between different architectural styles.

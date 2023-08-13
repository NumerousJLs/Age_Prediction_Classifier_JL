# Age_Prediction_Classifier_JL
This project involves processing and splitting a face dataset into training and testing sets using an 80-20 split. It utilizes feature extraction methods like SIFT to reduce the dimensionality of input images by converting face crops into N-dimensional linear feature vectors, with N set to 2048. The project also includes training a binary classifier for age group prediction using logistic regression and obtaining accuracy metrics on the test split. The dataset used will be the faces only wikipedia dataset from https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/

Additionally, methods to evaluate intersection over union from https://pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/ and location of faces in images using haar cascade are included from https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html

## Project Overview

The primary goal of this project is to predict age groups from face images using a machine learning approach. The process involves several steps, including dataset splitting, feature extraction using SIFT, training a logistic regression classifier, and evaluating its performance on a test split.

## Features

1. **Dataset Splitting:** The provided dataset is split into training and testing sets using an 80-20 split ratio.

2. **Feature Extraction:** Feature extraction is performed using the Scale-Invariant Feature Transform (SIFT) algorithm, resulting in N-dimensional linear feature vectors. In this project, N is set to 2048.

3. **Classifier Training:** A binary logistic regression classifier is trained on the extracted features to predict age groups buckets of 0-50 or 51-100.

4. **Performance Evaluation:** The accuracy of the trained classifier is evaluated using appropriate metrics on the test split.

After running the evaluate_classifier.py script, you'll obtain accuracy metrics that indicate how well the trained classifier predicts age groups on the test split.

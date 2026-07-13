# Lung-Cancer-Classification-from-Chest-CT-Scan-Images-Classical-ML-vs-ANN-

# Chest CT-Scan Classification

This project implements a multi-class image classification system to detect lung cancer types from chest CT-scan images. Classical machine learning models and an Artificial Neural Network (ANN) are trained and compared across four classes: Adenocarcinoma, Large Cell Carcinoma, Squamous Cell Carcinoma, and Normal.

## Features

* Automated dataset extraction and class-folder parsing
* Hash-based deduplication to remove train/test data leakage
* Image preprocessing (resizing to 64x64, normalization)
* Exploratory data analysis (class distribution, sample images)
* Multi-model classification (Logistic Regression, Decision Tree, Random Forest, SVM, KNN)
* Overfitting/underfitting diagnosis with PCA-based correction
* ANN implementation with BatchNormalization, Dropout, EarlyStopping, and ReduceLROnPlateau
* Evaluation via Accuracy, Precision, Recall, F1 Score, Confusion Matrix, and ROC Curve (macro-averaged)

## Technologies Used

* Python
* scikit-learn
* TensorFlow / Keras
* OpenCV
* pandas / numpy
* matplotlib / seaborn

## Files Included

* ChestCTScanClassfication.ipynb


Detailed documentation, methodology, and results are available directly in the project notebook.

## Dataset

Chest CT-Scan dataset (Kaggle) — not included in repo due to size.
Download and place as archive.zip in your Drive before running the notebook.

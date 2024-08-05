# Breast-cancer-detection-project

## Introduction

This project aims to predict whether a breast cancer case is benign or malignant based on features computed from digitized images of fine needle aspirate (FNA) of breast masses. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

## Dataset Description

The dataset consists of 569 instances of breast cancer cases, with 32 attributes:

1. **ID number**
2. **Diagnosis**: The diagnosis of breast tissues (M = malignant, B = benign)
3. **Features**: 30 real-valued features computed for each cell nucleus:
   - Radius (mean of distances from center to points on the perimeter)
   - Texture (standard deviation of gray-scale values)
   - Perimeter
   - Area
   - Smoothness (local variation in radius lengths)
   - Compactness (perimeter^2 / area - 1.0)
   - Concavity (severity of concave portions of the contour)
   - Concave points (number of concave portions of the contour)
   - Symmetry
   - Fractal dimension ("coastline approximation" - 1)

These features are computed as the mean, standard error, and "worst" or largest (mean of the three largest values) for each image, resulting in 30 features.

- **Class distribution**: 357 benign, 212 malignant
- **Missing attribute values**: None

## Steps to Predict Breast Cancer

### 1. Data Loading and Exploration

The first step involves loading the dataset and performing exploratory data analysis (EDA) to understand the distribution and characteristics of the data.

### 2. Data Preprocessing

Preprocessing the data includes:
- Handling missing values (if any)
- Encoding categorical variables
- Feature scaling

### 3. Splitting the Data

The dataset is split into training and test sets.

### 4. Model Building and Training

Different machine learning models are trained and evaluated:
- Logistic Regression
- Random Forest


### 5. Model Evaluation

The models are evaluated using metrics such as accuracy, precision, recall, and F1-score.

### 6. Hyperparameter Tuning

Hyperparameter tuning is performed to optimize the model's performance.

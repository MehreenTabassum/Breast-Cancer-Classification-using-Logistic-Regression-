# Breast Cancer Classification using Logistic Regression
This repository consists of an implementation of Logistic Regression for the classification of breast cancer cases based on medical data from a CSV file. This project uses the scikit-library for training and evaluation of the model. 
# Project Overview
- **Dataset:**  The breast cancer dataset contains 683 samples with following features of cell characteristics.
 -**Feature include:** Clump Thickness, Uniformity of Cell Size, Uniformity of Cell Shape, and more.
 -**Target:** Class (beningn or malignant)
- **Algorithm:** Logistic Regression
- **Libraries Used:**
  - `pandas` for data manipulation
  -  `scikit-learn` for model training and evaluation
  -  `numpy` for numerical operations
# Workflow
  1. **Data Preprocessing:**
     - The dataset is split into features (X) and target (y).
     - Features are further divided into training and test sets using an 80-20 split.
  2. **Model Training:**
     - A Logistic Regression model is trained on the training data.
  3. **Evaluation:**
    - Predictions are made on the test set. 
    - A confusion matrix is used to evaluate performance.
    - Accuracy is computed using k-Folds Cross Validation
# Files 
- `logistic_regression.py`: Python script for loading the dataset, training the logistic regression model, and evaluating it with cross-validation and confusion matrix.
- `breast_cancer.csv`: Dataset used for model traning and testing.
# How to Run 
1. Clone the repository:
```git clone https://github.com/MehreenTabassum/Breast-Cancer-Classification-using-Logistic-Regression-.git ```
3. Navigate to the project directory
  cd Breast-Cancer-Classification-using-Logistic-Regression-
4. Run the Python script:
   python logistic_regression.py
# Results
The model achieves good accuracy in classifying benign and malignant tumors. Cross-validation ensures the model's performance is robust, and the confuion matrix highlights correct and incorrect classififcations. 

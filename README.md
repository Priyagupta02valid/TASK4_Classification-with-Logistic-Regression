# TASK4_Classification-with-Logistic-Regression

# Logistic Regression Binary Classifier

## Overview
This project demonstrates how to build and evaluate a binary classification model using **Logistic Regression** with Python. The goal is to classify breast cancer tumors as malignant or benign based on the features in the Breast Cancer Wisconsin dataset.

## Dataset
The dataset used is the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the scikit-learn library. It contains 30 numeric features computed from digitized images of breast mass samples and a binary target variable indicating whether the tumor is malignant or benign.

## Tools & Libraries
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn
- NumPy

## Steps Performed
1. **Data Loading and Exploration**: Loaded the dataset and explored feature variables and target distribution.
2. **Train/Test Split & Feature Scaling**: Split the data into training and testing sets, then standardized features using `StandardScaler`.
3. **Model Training**: Trained a logistic regression model on the training data.
4. **Model Evaluation**: Evaluated the model using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC metrics.
5. **Threshold Tuning**: Adjusted the classification threshold to optimize precision and recall.
6. **Visualization**: Plotted confusion matrices, ROC curve, and the sigmoid function to explain logistic regression probabilities.

## Usage
- Run the provided Python script or Jupyter notebook.
- Modify the threshold to see its effect on classification metrics.
- Use the plots to better understand model performance and decision boundaries.

## Insights
- Logistic regression effectively separates the two classes.
- Threshold tuning allows balancing between precision and recall depending on the use case.
- Visualization of sigmoid function helps in understanding how raw model outputs translate into probabilities.

## License
This project is open-source and free to use for educational purposes.

---

Feel free to reach out if you have any questions or suggestions!

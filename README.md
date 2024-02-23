# Fraud Detection Model

## Overview
This repository contains a comprehensive fraud detection model that leverages data analysis and multiple machine learning algorithms to identify potentially fraudulent activities. The model has been trained and evaluated using various classifiers, showcasing high accuracy across different approaches.

## Key Features
- **Data Analysis:** Exploratory data analysis was performed to understand the dataset, identify patterns, and preprocess the data for model training.

- **Machine Learning Models:**
  - **DecisionTreeClassifier (Accuracy: 99.78%):** A decision tree-based classifier that excels in capturing complex decision boundaries.
  
  - **LogisticRegression (Accuracy: 99.25%):** A linear model suitable for binary classification tasks, providing a high level of interpretability.
  
  - **RandomForestClassifier (Accuracy: 99.72%):** An ensemble of decision trees that enhances predictive performance through aggregation.
  
  - **KNeighborsClassifier (Accuracy: 99.09%):** A proximity-based classifier that classifies instances based on the majority class of their k-nearest neighbors.
  
  - **SVC (Accuracy: 88.12%):** Support Vector Classifier, a powerful algorithm for binary classification, though with comparatively lower accuracy in this context.
  
  - **Ensemble Model (Accuracy: 99.75%):** An ensemble approach combining multiple models to improve overall predictive performance.

## Dataset
The model was trained on the [Online Payments Fraud Detection Dataset](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset?resource=download). Please refer to the dataset link for additional details on the data.

## How to Use
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `fraud_detection.py` script to train and evaluate the models on your dataset.
4. Customize the models and parameters based on your specific use case.
5. Explore the Jupyter notebooks (`notebooks/`) for in-depth analysis and visualization.

Feel free to contribute, report issues, or suggest improvements. Happy detecting!

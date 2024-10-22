# Breast Cancer Diagnosis using Machine Learning

## Project Overview
This project aims to develop a machine learning model to accurately diagnose breast cancer using the Breast Cancer Wisconsin (Diagnostic) dataset. The goal is to assist healthcare professionals in making informed decisions by utilizing advanced data analysis techniques.

## Dataset
The dataset consists of 569 samples with 32 features. The features include various characteristics of cell nuclei that are important for distinguishing between malignant and benign tumors.

- **ID:** Unique identifier for each sample.
- **Diagnosis:** Diagnosis of the tumor (M = malignant, B = benign).
- **Features:** 
  - Feature_1 to Feature_30 represent different measurements related to the cell nuclei, such as radius, texture, perimeter, area, smoothness, and compactness.

## Exploratory Data Analysis (EDA)
Before modeling, the dataset was analyzed to understand the relationships between variables and the distribution of diagnoses. Key findings include:
- The dataset has no missing values.
- Certain features, such as radius and area, show strong correlations with the diagnosis.

## Model Development
Two machine learning models were implemented:
1. **XGBoost Classifier** - A powerful gradient boosting framework known for its performance in classification tasks.
2. **Artificial Neural Network (ANN)** - A deep learning model designed to mimic the way the human brain operates.

### Hyperparameter Tuning
Hyperparameters for both models were tuned to optimize performance, including:
- Number of trees and learning rate for XGBoost.
- Architecture of the ANN, including the number of layers and nodes.

## Model Evaluation
Both models were evaluated using metrics such as:
- Precision
- Recall
- F1-Score
- AUC-ROC

Results:
- **XGBoost:**
  - Accuracy: 96%
  - AUC-ROC: 0.95
- **ANN:**
  - Accuracy: 96%
  - AUC-ROC: 0.96

## Results and Improvements
The models demonstrated high accuracy in classifying breast cancer diagnoses. Future improvements could include:
- Feature selection to enhance model performance.
- Further hyperparameter tuning for better optimization.
- Exploring transfer learning techniques for ANN.

## Importance of the Model
The development of a reliable machine learning model for breast cancer diagnosis can lead to:
- Faster and more accurate diagnoses.
- Reduced costs in healthcare by automating the diagnostic process.
- Improved patient outcomes through better clinical decision-making.

## Conclusion
This project highlights the potential of machine learning in the healthcare industry, particularly in improving diagnostic accuracy for breast cancer. By leveraging data and advanced algorithms, we can enhance patient care and support medical professionals in their crucial work.

## Getting Started
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Breast-Cancer-Diagnosis-ML.git

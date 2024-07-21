# Predicting Survival Status of Patients with Liver Cirrhosis

This project aims to develop and validate machine learning algorithms for predicting the survival status of patients with liver cirrhosis using a dataset from a Mayo Clinic study on primary biliary cirrhosis (PBC) of the liver.

## Project Overview

### Objective

The objective of this project is to:
1. Accurately predict the survival status of patients using 17 clinical features.
2. Explain the prediction and identify key factors associated with the survival status.

### Dataset

- **Source**: Mayo Clinic study on primary biliary cirrhosis (PBC) of the liver (1974-1984).
- **Size**: 312 patients (224 for training and 88 for testing).
- **Features**: 17 clinical features.
- **Survival Status**:
  - 0 = D (death)
  - 1 = C (censored)
  - 2 = CL (censored due to liver transplantation)

## Instructions Followed

### Data Exploration and Pre-processing

1. **Load and Explore the Dataset**:
   - Show training and test dataset size.
   - Identify feature types and missing values.
   - Handle missing values appropriately.
   - Encode categorical features.
   - Show label distribution and check if the training set is balanced.

2. **Supervised Machine Learning Models**:
   - Create three ML models to predict "Status".
   - Use appropriate validation methods and report performance scores.
   - Justify design decisions and hyper-parameter optimization.
   - Address label imbalance issues.
   - Recommend the best model based on results.

3. **Prediction on Test Set**:
   - Use the best model to predict on the pre-processed test set.
   - Save predictions (testID and Status) and submit to Kaggle in-class platform.
   - Report model performance with a screenshot.

4. **Feature Importance Analysis**:
   - Analyze feature importance using two different approaches.
   - Provide statistical reasons for findings.

## Results

The Jupyter notebook containing the code and outputs, as well as the report summarizing the findings, are presented in this repository.

## Technologies Used

- `Python`
- `Jupyter Notebook`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Installation

To run the analysis, you need to have Python and the necessary libraries installed. You can install the required libraries using the following command:

```bash
pip install pandas scikit-learn matplotlib seaborn

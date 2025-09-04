# Loan Approval Prediction

## Overview
This project predicts loan approval based on applicant details using the Loan-Approval-Prediction-Dataset from Kaggle. It handles missing values, encodes categorical features, trains classification models, and evaluates on imbalanced data. Bonus: SMOTE for imbalance, logistic regression vs. decision tree.

## Features
- Loads and preprocesses data with Pandas.
- Handles imbalance with SMOTE.
- Trains Logistic Regression and Decision Tree models.
- Evaluates with precision, recall, F1-score, and confusion matrices.
- Bonus: Model comparison and imbalance techniques.

## Requirements
  Python 3.12+
  Dataset: Loan-Approval-Prediction-Dataset (downloaded from https://www.kaggle.com/datasets/sonujha090/loan-approval-prediction-dataset)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd loan-approval-prediction
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage
1. Run the Jupyter Notebook `loan_approval_prediction.ipynb`:
   ```bash
   jupyter notebook loan_approval_prediction.ipynb
   ```
2. Execute cells sequentially to load data, train models, and view visualizations/results.
3. Adjust file paths or parameters in the code as needed.

## File Structure
- `loan_approval_prediction.ipynb`: Main notebook with code and analysis.
- `loan_approval_dataset.csv`: Dataset
- `README.md`: This file.

## Results
- Logistic Regression: High accuracy on balanced data.
- Decision Tree: Improved recall with SMOTE.
- Visualizations: Confusion matrices, comparison reports.

## Acknowledgments
- Dataset from Kaggle (Loan-Approval-Prediction-Dataset).


### Instructions
- Replace `<repository-url>` with your actual GitHub repository URL.
- Save this as `README.md` in your `loan-approval-prediction` repository.
- Ensure the `loan_approval_prediction.ipynb` notebook is included in the same directory.
- Upload to GitHub using the steps provided earlier (via "Upload files" or Git commands).

Let me know if you need further assistance!

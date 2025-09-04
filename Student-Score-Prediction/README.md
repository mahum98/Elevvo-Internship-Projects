# Student Score Prediction

## Overview
This project builds a model to predict students' exam scores based on study hours and other factors using the Student Performance Factors dataset from Kaggle. It includes data cleaning, visualization, linear regression training, predictions, and evaluation. Bonus: Polynomial regression and feature combinations.

## Features
- Loads and cleans the dataset with Pandas.
- Visualizes data trends and correlations.
- Trains Linear Regression and Random Forest models.
- Evaluates with metrics like R² and MSE.
- Bonus: Polynomial regression comparison and feature experimentation (e.g., sleep, participation).

## Requirements
  Python 3.10+
  Dataset: Student Performance Factors (download from https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd student-score-prediction
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib scikit-learn
   ```
## Usage
1. Run the Jupyter Notebook `Student_Score_Prediction.ipynb`:
   ```bash
   jupyter notebook Student_Score_Prediction.ipynb
   ```
2. Execute cells sequentially to load data, train models, and view visualizations/results.
3. Adjust file paths or features in the code as needed.

## File Structure
- `Student_Score_Prediction.ipynb`: Main notebook with code and analysis.
- `StudentPerformanceFactors.csv`: Dataset. 
- `README.md`: This file.

## Results
- Linear Regression: Predicts scores based on study hours.
- Random Forest: Improves accuracy with additional features.
- Visualizations: Scatter plots, feature importance, predictions vs. actual.

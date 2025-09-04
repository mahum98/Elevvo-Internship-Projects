
# Forest Cover Type Classification
This repository hosts a Python project for classifying forest cover types using the Covertype dataset from UCI. It leverages cartographic and environmental features to predict one of seven cover types, utilizing multi-class classification models.
## Overview
 **Dataset**: Covertype (UCI Machine Learning Repository).
 
 **Goal**: Predict forest cover type (1-7) from 54 features.
 
 **Models**: Random Forest, XGBoost with hyperparameter tuning.
 
 **Tools**: Python, Pandas, Scikit-learn, XGBoost, Seaborn, Matplotlib.
## Features
- Extracts and loads `covertype.zip` containing `covtype.data.gz` in Google Colab.
- Preprocesses data, handling categorical wilderness and soil type indicators.
- Trains and compares Random Forest and XGBoost models.
- Visualizes confusion matrices and feature importances.
- Includes hyperparameter tuning with GridSearchCV.
## Setup
1.	Clone the repository:
      git clone https://github.com/your-username/forest-cover-classification.git
2.	Install dependencies: 
      pip install pandas numpy scikit-learn xgboost seaborn matplotlib
3.	Upload the covertype.zip dataset to Google Colab's session storage.
## Usage
1.	Open the notebook in Google Colab.
2.	Execute cells in order to extract data, preprocess, train models, and generate visualizations.
3.	Modify zip_file or column names if the dataset structure differs.
## Notes
•	Ensure the dataset is uploaded correctly via the "Files" tab.
•	Label shifting (1-7 to 0-6) is applied for XGBoost compatibility.
•	Expand param_grid for more tuning options if desired.


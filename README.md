# InstaFraudDetection

**InstaFraudDetection** is a comprehensive machine learning project designed to detect fake accounts on Instagram using various classification algorithms. This project utilizes visualizations to explore data and employs machine learning techniques for model training and evaluation.

## Features

- **Exploratory Data Analysis (EDA):** Utilizes visualizations to understand data distributions and relationships.
- **Data Preprocessing:** Handles missing values and removes duplicates to prepare data for modeling.
- **Machine Learning Classifiers:** Implements several classifiers to detect fake accounts:
  - Random Forest Classifier
  - XGBoost Classifier
  - LightGBM Classifier
  - CatBoost Classifier
  - AdaBoost Classifier
- **Model Evaluation:** Assesses model performance using the ROC-AUC score and interprets predictions with SHAP values.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SumanR1602/InstaFrauddetection.git
   cd InstaFraudDetection
2. **Install the required packages:**
   ```bash
   pip install scikit-learn
   pip install shap
   pip install catboost
   pip install plotly
   pip install matplotlib
   pip install seaborn
  
3.**Download datasets:** Datasets can be found on Kaggle
  - train.csv: The training dataset containing user features and labels.
    
  - test.csv: The test dataset for evaluating model performance.
  
4.**Results:**
  - The project evaluates the performance of the trained classifiers using metrics such as ROC-AUC score.
  - Visualizations of feature distributions and SHAP values are included to interpret model predictions.

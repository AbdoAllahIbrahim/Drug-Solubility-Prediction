
# Diabetes Readmission Prediction

## Project Overview
This project focuses on predicting hospital readmissions for diabetic patients using various machine learning techniques. It explores different algorithms and optimizes performance to provide accurate predictions.

## Features
- **Data Preprocessing**: Handled missing values and data imbalances through imputation and oversampling.
- **Algorithms Used**: Logistic Regression, Random Forest, XGBoost.
- **Model Evaluation**: Employed cross-validation and optimized with performance metrics such as AUC-ROC and F1-score.

## Installation

### Requirements
- Python 3.x
- Libraries: pandas, scikit-learn, xgboost, matplotlib, seaborn

### Setup Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/diabetes-readmission-prediction.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to view the model training and evaluation:
   ```bash
   jupyter notebook
   ```

## Usage
The project processes the dataset and builds machine learning models to predict the likelihood of patient readmission based on various health factors.

1. **Preprocessing**: Apply missing data imputation and oversampling to balance the dataset.
2. **Model Training**: Train and evaluate different classification models using cross-validation.
3. **Prediction**: Use the best-performing model to predict patient readmission probabilities.

## Results
The final model demonstrated strong predictive performance with the following key metrics:
- **AUC-ROC**: 0.89
- **F1-Score**: 0.74


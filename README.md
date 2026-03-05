# Ensemble Learning: Obesity Risk Prediction Project

This project demonstrates the application of **Ensemble Learning techniques** for predicting obesity risk levels. By leveraging multiple machine learning models and combining their predictions, the project aims to achieve more accurate and robust classification compared to individual models.

## Objective
To classify individuals into different obesity risk categories based on lifestyle, demographic, and health-related features using various ensemble methods.

## Dataset
The project uses a dataset containing features related to individuals' habits, demographics, and health metrics to predict obesity levels (target variable: `NObeyesdad`).

## Key Features
- **Data Preprocessing**: Includes dropping irrelevant columns, label encoding categorical variables, feature scaling, and train-test splitting (80-20 ratio).
- **Models Implemented**:
  - Traditional Models: Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN)
  - Ensemble Models: Random Forest (Bagging), AdaBoost, XGBoost, Gradient Boosting, Voting Classifiers (Hard/Soft/Weighted), Stacking, and Blending
- **Evaluation**: Metrics include Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and Classification Report.

## Results
The ensemble methods, particularly XGBoost, demonstrated superior performance in terms of accuracy and generalization. A comprehensive comparison of all models is provided in the notebook.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

## How to Run
1. Clone the repository.
2. Ensure `dataset.csv` is in the project directory.
3. Open `Ensemble_Learning.ipynb` in Jupyter Notebook.
4. Run the cells sequentially to execute data preprocessing, model training, and evaluation.

## About This Project
This was a beginner project that introduced me to practical machine learning applications, particularly ensemble learning techniques for classification tasks. It served as a foundational step in my journey into data science and AI.

## Author
Ojas Sahu (2023A3PS0861G)


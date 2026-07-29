# Patient Readmission Prediction

## Project Overview
This project uses machine learning to predict whether a patient is likely to be readmitted within 30 days of discharge. The project includes data preprocessing, exploratory data analysis (EDA), feature selection, model building, and model evaluation.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Databricks
- GitHub
- Plotly express
- Seaborn

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC


## Conclusion
The Logistic Regression model achieved a testing accuracy of 49.50%, precision of 28.04%, recall of 47.98%, F1 Score of 35.39%, and a ROC-AUC score of 49.26%. The ROC curve showed that the model has limited ability to distinguish between readmitted and non-readmitted patients. The small difference between the training accuracy (51.12%) and testing accuracy (49.50%) indicates that there is no strong evidence of overfitting. However, the model's predictive performance remains limited, suggesting that further improvements such as feature engineering, hyperparameter tuning, and better handling of class imbalance could improve its performance.

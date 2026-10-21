Predictive Churn Analysis
Project Overview
This project uses Machine Learning to predict customer churn and generate a churn-risk score for each customer.
Objective
- Predict customer churn
- Identify high-risk customers
- Apply One-Hot Encoding and MinMax scaling
- Use an 80/20 train-test split
- Evaluate Precision, Recall, F1-Score and ROC-AUC
- Export customer risk predictions
Files
- churn_prediction.ipynb – reproducible ML notebook
- churn_dataset.csv – project dataset
- churn_risk_predictions.csv – customer-level churn probabilities and risk levels
- churn_analysis_report.pdf – project report
- roc_auc_curve.png – ROC-AUC visualization
- README.md – project documentation
Model
Logistic Regression with a scikit-learn preprocessing pipeline.
Risk Levels
- Low: < 0.40
- Medium: 0.40–0.69
- High: >= 0.70
How to Run
pip install pandas numpy scikit-learn matplotlib
Open churn_prediction.ipynb in Jupyter Notebook or Google Colab and run the cells.
Note
The included dataset is a reproducible sample created for this project because no specific source dataset was provided. Replace it with your required dataset if your college/internship portal supplied one.

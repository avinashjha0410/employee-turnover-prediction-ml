# Employee Turnover Prediction using Machine Learning

## Project Objective
The goal of this project is to predict employee turnover using machine learning techniques. The model identifies employees who are likely to leave the company and helps HR departments implement targeted retention strategies.

## Dataset
The dataset contains employee work information including:

- Satisfaction level
- Last evaluation score
- Number of projects
- Average monthly hours
- Time spent at company
- Department
- Salary level
- Promotion history
- Work accidents

## Techniques Used

### Exploratory Data Analysis (EDA)
- Correlation heatmap
- Distribution plots
- Boxplots
- Department-wise analysis
- Salary impact analysis

### Clustering
K-Means clustering was used to identify different groups of employees who left the organization.

### Handling Class Imbalance
SMOTE (Synthetic Minority Oversampling Technique) was applied to balance the dataset.

### Machine Learning Models
- Logistic Regression
- Random Forest
- Gradient Boosting

### Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Best Model
Random Forest achieved the best performance with high accuracy and recall in predicting employee turnover.

## Business Impact
The model categorizes employees into risk zones based on turnover probability:

- Safe Zone
- Low Risk
- Medium Risk
- High Risk

This allows HR teams to implement proactive retention strategies.

## Author
Avinash Kumar Jha

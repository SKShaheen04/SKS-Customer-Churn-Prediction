# SKS-Customer-Churn-Prediction
# Customer Churn Prediction Using Machine Learning

## 1. Project Overview
Customer Churn Prediction is a machine learning project that predicts whether a customer is likely to leave a telecom service. The project uses classification algorithms to analyze customer information and identify patterns related to customer churn.

## 2. Problem Statement
Customer churn is a major challenge for telecom companies. Losing customers can affect business growth and revenue. This project aims to predict customer churn using machine learning techniques so that companies can identify customers who may leave their services.

## 3. Objectives
- Analyze customer data to identify churn patterns.
- Perform data cleaning and preprocessing.
- Visualize important customer information.
- Build machine learning classification models.
- Compare model performance using evaluation metrics.

## 4. Dataset Description
- **Dataset:** Telco Customer Churn
- **Source:** Kaggle
- **Records:** 7,043
- **Features:** 21 columns
- **Target Variable:** Churn

Dataset link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains customer details such as tenure, contract type, monthly charges, payment method, and service information.

## 5. Data Preprocessing
The following preprocessing steps were performed:
- Converted `TotalCharges` into numeric format.
- Handled 11 missing values by filling them with 0.
- Checked for duplicate records.
- Removed the `customerID` column before model training.
- Prepared the data for machine learning.

## 6. Data Visualization
The project includes four visualizations:
1. Customer Churn Distribution
2. Churn by Contract Type
3. Customer Tenure Distribution
4. Monthly Charges vs Churn

These visualizations help understand customer behavior and identify factors associated with churn.

## 7. Machine Learning Algorithms

### Logistic Regression
Logistic Regression is a classification algorithm used to predict whether a customer will leave or continue using the service.

### Random Forest
Random Forest is an ensemble learning algorithm that combines multiple decision trees to make predictions.

## 8. Model Performance

The models were evaluated using Accuracy, Precision, Recall, and F1-score.

| Evaluation Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 73.81% | 78.28% |
| Precision | 50.43% | 61.89% |
| Recall | 78.34% | 47.33% |
| F1-score | 61.36% | 53.64% |

### Confusion Matrices
Confusion matrices were used to compare actual and predicted customer churn classifications for both models.

### Performance Comparison
Random Forest achieved higher accuracy and precision, while Logistic Regression achieved higher recall and F1-score.

## 9. Conclusion
This project demonstrates how machine learning can be used to predict customer churn. Both Logistic Regression and Random Forest were implemented and evaluated. The results show that Logistic Regression identifies more customers who are likely to churn, while Random Forest achieves higher overall accuracy.

## 10. Limitations
- The prediction depends on the available dataset.
- Model performance may vary with different data.
- Additional features and model tuning may improve the results.

## 11. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 12. Project Files
- `Customer_Churn_Prediction_Updated.ipynb` – Project implementation and analysis.
- `Customer_Churn_Prediction_Project_Report.pdf` – Project documentation.

## 13. Author
**Shaik Shaheen**


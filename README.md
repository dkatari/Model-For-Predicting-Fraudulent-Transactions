# Model-For-Predicting-Fraudulent-Transactions
## Objective
The notebook aims to detect fraudulent transactions using machine learning models.

## Data Overview
- The dataset contains 6,362,620 entries and 11 columns.
- Columns include information like transaction type, amount, origin and destination balances, and fraud indicators.

## Data Preprocessing
- Handling missing values and duplicates.
- Encoding categorical variables.
- Scaling numerical features.

## Exploratory Data Analysis
- Univariate analysis: Understanding the distribution of variables.
- Bi-variate analysis: Correlation analysis among numerical features.

## Model Building
### Logistic Regression:
- Applied using both holdout technique and cross-validation.
- Holdout Technique: Achieved high accuracy but low recall for fraud detection.
- Cross-Validation: Provided a more reliable measure of model performance but still showed low recall for fraud.
### Decision Tree:
- Applied using the holdout technique.
- Achieved high accuracy and significantly higher recall for fraud detection compared to Logistic Regression.

## Model Comparison
- Accuracy: Decision Tree outperformed Logistic Regression.
- Recall for Fraud Detection: Decision Tree showed much higher recall compared to Logistic Regression.

## Recommendation
- Decision Tree using the holdout technique is recommended due to its high accuracy and significantly better ability to detect fraud compared to Logistic Regression.
- Decision Tree's performance remained consistent across different training/test splits, indicating reliability in detecting fraudulent transactions.

## Conclusion
- Decision Tree model is preferred for fraud detection due to its balance between accuracy and ability to detect fraud.
- Cross-validation provides a more reliable measure of model performance compared to the holdout technique, but Decision Tree still outperformed Logistic Regression in both scenarios.

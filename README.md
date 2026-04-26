# Customer Churn Prediction

## Objective
Predict whether a customer will leave the service.

## Dataset
Telco Customer Churn (Kaggle)

## Steps
- Cleaned data (converted TotalCharges to numeric, handled missing values)
- Selected relevant features (tenure, charges, services, contract)
- Encoded categorical variables using one-hot encoding
- Trained Random Forest classifier

## Result
Achieved ~79% accuracy on test data.

## Key Learning
- Handling categorical data is crucial
- Feature selection significantly impacts performance
- Real-world data requires preprocessing before modeling

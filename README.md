# House Price Prediction

This project builds a machine learning model to predict house prices using the House Price dataset.

## Techniques Used
- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Dummy Variable Encoding
- Log Transformation of Target Variable
- Linear Regression

## Model Performance
- R² Score: 0.731
- Adjusted R²: 0.695

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Workflow
1. Load and clean dataset
2. Remove rows where SalePrice is missing
3. Convert categorical variables using dummy encoding
4. Apply feature engineering
5. Train Linear Regression model
6. Evaluate using R² and Adjusted R²

## Result
The final model explains around **73% of the variance in house prices**, demonstrating a strong baseline regression model.

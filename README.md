# Salary Prediction Regression

This project predicts employee salaries based on their **experience** and **test scores** using **linear regression** models. It demonstrates both **single feature** and **multiple feature** regression, evaluates model performance, and saves the best model for future use.

## **Features**
- Single feature regression (Experience → Salary)
- Multiple feature regression (Experience + TestScore → Salary)
- Handles categorical features if present
- Train/test split for model evaluation
- Model evaluation using **RMSE** and **R²**
- Saves the best model using `joblib`

## **Dataset**
- The dataset contains the following columns:
  - `Experience`: Years of experience of the employee
  - `TestScore`: Test score of the employee
  - `Salary`: Target variable (salary in USD or local currency)

Usage
Load the dataset (Salary_Data.csv) into the project folder.
Run the Python script:
python salary_prediction.py
The script will:
Train single and multiple linear regression models
Evaluate models using RMSE and R²
Save the best-performing model as BestSalaryModel.pkl

Results
Compare single vs multiple feature models based on RMSE and R².
Use the saved model for future predictions without retraining.

Future Improvements
Add more features like Education, Department, or Location
Implement polynomial regression for non-linear trends
Visualize feature importance and residual plots
Deploy the model as a web app using Flask or Streamlit

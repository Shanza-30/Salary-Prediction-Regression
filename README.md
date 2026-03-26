# 💼 Salary Prediction using Linear Regression

This project task 1 syntecxhub predicts employee salaries based on their **years of experience** and **test scores** using **Linear Regression**. It demonstrates both **single-feature** and **multi-feature** regression approaches, compares their performance, and saves the best-performing model for future predictions.


## 🚀 Project Highlights

* 📈 **Single Feature Regression**: Experience → Salary
* 📊 **Multiple Feature Regression**: Experience + TestScore → Salary
* 🧹 Data preprocessing and handling of categorical features (if present)
* 🔀 Train–test split for fair model evaluation
* 📐 Model evaluation using **RMSE** and **R² Score**
* 💾 Saves the best model using `joblib` for reuse


## 📂 Dataset Information

The dataset includes the following columns:

* **Experience**: Years of professional experience
* **TestScore**: Employee test or assessment score
* **Salary**: Target variable (salary in USD or local currency)

> Dataset file: `Salary_Data.csv`


## ⚙️ How to Use

1. Clone the repository or download the project files.
2. Place the dataset file `Salary_Data.csv` in the project directory.
3. Run the Python script:

   ```bash
   python salary_prediction.py
   ```
   
## 🧠 What the Script Does

* Loads and explores the dataset
* Trains:

  * A **single-feature linear regression model**
  * A **multiple-feature linear regression model**
* Evaluates both models using:

  * **Root Mean Squared Error (RMSE)**
  * **R² Score**
* Compares performance and selects the best model
* Saves the best-performing model as:

  ```
  BestSalaryModel.pkl

## 📊 Results

* Performance comparison between single and multiple feature models is done using **RMSE** and **R²**.
* The model with lower RMSE and higher R² is selected as the final model.
* The saved model can be used later for predictions without retraining.


## 🔮 Future Improvements

* ➕ Add more predictive features such as **Education**, **Department**, or **Location**
* 📈 Implement **Polynomial Regression** to capture non-linear relationships
* 📉 Visualize **residual plots** and **feature importance**
* 🌐 Deploy the model as a **Flask** or **Streamlit** web application
* 🤖 Experiment with advanced regression models (Ridge, Lasso, Random Forest)


## 🛠️ Tools & Technologies

* Python
* Pandas & NumPy
* scikit-learn
* joblib
* Matplotlib / Seaborn (optional for visualization)


## 📌 Conclusion

This project provides a clear and practical introduction to regression-based salary prediction, covering model training, evaluation, comparison, and deployment readiness. It is ideal for beginners learning **machine learning regression concepts** and **end-to-end ML workflows**.

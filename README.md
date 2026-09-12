# PRODIGY_ML_01 - House Price Prediction

This repository contains the solution for **Task-01** of the Machine Learning Internship at **Prodigy InfoTech**.

## 📌 Project Overview
The objective of this task is to implement a **Linear Regression** model to predict house prices based on specific features like square footage, the number of bedrooms, and the number of bathrooms using the Housing Prices dataset.

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **Libraries:** 
  * `pandas` for data manipulation
  * `scikit-learn` for machine learning model and evaluation metrics

## 📊 Methodology & Steps
1. **Data Loading:** Loaded the dataset using Pandas.
2. **Feature Engineering & Selection:** Selected key predictive features (`GrLivArea`, `BedroomAbvGr`, and combined total bathrooms from Full and Half bathrooms) and handled missing values using the median.
3. **Data Splitting:** Split the dataset into training and testing sets (80% train, 20% test).
4. **Model Training:** Trained a Linear Regression model using `scikit-learn`.
5. **Evaluation:** Evaluated model performance using:
   * **$R^2$ Score:** Measures the goodness of fit.
   * **Root Mean Squared Error (RMSE):** Measures prediction error magnitude.

## 📈 Results
* **$R^2$ Score:** 0.6286
* **RMSE:** 53371.56

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/PRODIGY_ML_01.git](https://github.com/your-username/PRODIGY_ML_01.git)

# 🚗 Car Price Prediction using Machine Learning Models  

## 📋 Overview  
This project aims to **predict the price of used cars** based on various attributes such as year, mileage, engine size, fuel type, and transmission type.  
Using multiple machine learning models, this analysis identifies which features most strongly influence car prices and determines the best-performing model for accurate predictions.  

---

## 🎯 Objective  
To build and evaluate machine learning models that accurately predict car prices using numerical and categorical features from a Kaggle dataset.  

---

## 🧩 Dataset  
The dataset was sourced from **Kaggle**, containing information on:  
- Year of manufacture  
- Mileage  
- Tax  
- MPG (Miles per Gallon)  
- Engine Size  
- Transmission type  
- Fuel type  
- Other categorical features related to efficiency and tax categories  

---

## 🧠 Machine Learning Models Used  
The following regression models were implemented and compared:  
1. **Linear Regression**  
2. **Ridge Regression**  
3. **Lasso Regression**  
4. **Decision Tree Regressor**  
5. **Random Forest Regressor** ✅ *(Best Performing Model)*  

---

## 📊 Model Evaluation Metrics  
Each model was evaluated on:  
- **R² Score**  
- **Mean Absolute Error (MAE)**  
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  

**Best Results (Random Forest Regressor):**  
- **R² Score:** 0.9087  
- **MAE:** 2081.44  
- **MSE:** 11,797,885.30  
- **RMSE:** 3434.80  

---

## 📈 Feature Importance  
Feature importance analysis using Random Forest revealed that:  
- **Year**, **Engine Size**, and **MPG** were the top contributors to predicting car prices.  

---

## ⚙️ Technologies & Libraries  
- **Python** 🐍  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computation  
- **Matplotlib** & **Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models and evaluation metrics  

---

## 🚀 Future Work  
- Implement **hyperparameter tuning** (GridSearchCV / RandomizedSearchCV) for model optimization.  
- Add **cross-validation** for more robust evaluation.  
- Deploy the final model using **Streamlit** or **Flask** for interactive price prediction.  

---

## 🧑‍💻 Author  
**Himanshu Kapoor**  
📍 Data Analyst 
  

## 🧰 How to Run the Project Locally  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Himanshu1761/Car-Price-Prediction.git
   cd Car-Price-Prediction

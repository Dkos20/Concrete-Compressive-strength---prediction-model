# Concrete Compressive Strength Prediction

This project focuses on predicting the **compressive strength of concrete** using **machine learning techniques**, specifically the **XGBoost** algorithm. The goal is to build a regression model that accurately estimates the strength of concrete based on its ingredients and curing time.

## 📌 Overview

Concrete compressive strength is a critical parameter in construction and civil engineering. In this project, a dataset containing features such as cement content, water, age, and additives was analyzed and preprocessed to train a predictive model.

Key steps included:
- Data exploration and visualization
- Feature engineering (e.g., water/cement ratio)
- Outlier handling and transformation
- Model training using XGBoost
- Evaluation using RMSE, MAE, and R² with 5-fold cross-validation

> **Result**: The model achieved strong performance, with an RMSE of ~4.51 MPa and R² of ~0.92, showing reliability for real-world application.

## 🔧 Technologies Used

- 🐍 **Python** (data analysis & modeling)
- 📊 **Pandas, NumPy** (data manipulation)
- 📈 **Matplotlib, Seaborn** (visualization)
- 💡 **Scikit-learn** (cross-validation, metrics)
- ⚙️ **XGBoost** (regression model)
- 🧪 **Jupyter Notebook** (experimentation)
- ☁️ **Google Colab** (cloud-based environment)

## 📂 Dataset

The dataset `Concrete_data.csv` contains the following input features:
- Cement, Blast Furnace Slag, Fly Ash, Water, Superplasticizer, Coarse Aggregate, Fine Aggregate, Age (days)

**Target variable**: `Concrete compressive strength (MPa)`

## 🔗 Notebook

👉 [Click here to open the Colab notebook](https://colab.research.google.com/drive/1TRJDGhQju-BqhzLNmT8vi-rM4elUh6PK?usp=sharing)

## 📜 License

This project is developed as part of an academic assignment at the **University of Zagreb, Faculty of Organization and Informatics (FOI)**. Free to use with attribution.


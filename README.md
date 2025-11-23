# 🏡 House Price Prediction using Machine Learning  
A complete end-to-end **Regression Machine Learning Project** that predicts house prices based on features such as area, number of bedrooms, location, and construction year.

This project includes **data cleaning, visualization, outlier handling, encoding, scaling, model building, and model evaluation** — making it a perfect beginner-friendly ML portfolio project.

---

## 🚀 Project Overview
This project predicts **house prices** using multiple machine learning regression algorithms.  
It follows real-life industry workflow:

1. Loading data  
2. Handling missing values  
3. Detecting & fixing outliers  
4. Exploratory Data Analysis (EDA)  
5. Encoding categorical variables  
6. Feature scaling  
7. Model training  
8. Evaluation & comparison  

---

## 📂 Dataset Description
Dataset contains:

| Feature | Description |
|---------|-------------|
| Area | Size of the house in square feet |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Location | Area/City of the property |
| Year | Construction year |
| Price | Target variable (house price) |

Dataset includes **missing values + outliers**, which makes it perfect for ML practice.

---

## 🔧 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  

---

# 🧹 1. Data Preprocessing

### ✔️ Missing Value Handling  
- Numerical → Mean/Median  
- Categorical → Mode  

### ✔️ Outlier Detection  
- Boxplots  
- IQR Method  
- Capping extreme values  

### ✔️ Encoding  
- Label Encoding  
- One-Hot Encoding (for location)  

### ✔️ Feature Scaling  
- StandardScaler for algorithms like Linear Regression & SVR  

---

# 📊 2. Exploratory Data Analysis (EDA)

Included visualizations:

- Price distribution  
- Area vs Price scatter plot  
- Heatmap (correlation matrix)  
- Boxplots for outliers  
- Pairplot across important features  

These help understand patterns & relations in housing data.

---

# 🤖 3. Machine Learning Models Used

| Model | Notes |
|-------|-------|
| Linear Regression | Simple + baseline |
| Decision Tree Regressor | Captures non-linear patterns |
| Random Forest Regressor | High accuracy ensemble |
| Support Vector Regressor (SVR) | Performs well after scaling |

---

# 🧪 4. Model Evaluation  
Metrics used:

- **MAE (Mean Absolute Error)**  
- **MSE (Mean Squared Error)**  
- **RMSE (Root Mean Squared Error)**  
- **R² Score**  

A comparison table is shown at the end to pick the best model.

> In most cases, **Random Forest** gives the highest accuracy for house price prediction.

---

# 🏆 Final Results  
All models are trained and evaluated.  
Final model selected based on:

- Highest R² Score  
- Lowest RMSE  

---

# 📁 Project Structure  

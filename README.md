# 📊 Data Analysis Projects – Machine Learning with Python

This repository contains two end-to-end data analysis projects using regression techniques to generate insights and predictive models from real-world datasets.

1. 🏥 **Insurance Cost Prediction**  
2. 🏠 **House Price Analysis (King County)**  

---

## 🧭 5-Step Workflow Followed in Both Projects

### ✅ Step 1: Import the Dataset  
- Loaded raw `.csv` files using `pandas`.

### ✅ Step 2: Data Wrangling  
- Replaced unknowns (`?`) with `NaN`, then filled missing values using mode/mean.  
- Renamed columns for clarity, converted datatypes, rounded values.  
- Ensured clean and structured DataFrame ready for analysis.

### ✅ Step 3: Exploratory Data Analysis (EDA)  
- Used `Seaborn` and `Matplotlib` for visualization:  
  - `regplot` → `charges` vs `bmi`  
  - `boxplot` → `smoker` vs `charges`  
  - Examined patterns, distributions, and correlations among features.

### ✅ Step 4: Model Development  
- Built regression models using `scikit-learn`:  
  - **Linear Regression**  
  - **Polynomial Regression**  
  - **Pipeline modeling** for streamlined workflow  
- Trained models using `.fit()` and evaluated with `r2_score()`.

### ✅ Step 5: Model Refinement  
- Performed `train_test_split` (80-20 split).  
- Applied **Ridge Regression** to reduce overfitting.  
- Enhanced accuracy with `PolynomialFeatures` for non-linear feature interaction.  
- Final model predictions evaluated using R² on test data.

---

## 🏥 Project 1: Insurance Cost Prediction

### 🎯 Objective:  
Predict medical insurance charges based on demographic and health-related features.

### 💡 Key Features Used:
- `age`, `bmi`, `smoker`, `region`, `gender`, `no_of_children`

### 🔍 What Was Done:
- Cleaned and imputed missing values  
- Visualized relationships like `charges vs bmi`, `smoker vs charges`  
- Trained models (Linear, Polynomial, Ridge)  
- Achieved improved predictive accuracy using model tuning and pipelines

---

## 🏠 Project 2: House Price Analysis (King County)

### 🎯 Objective:  
Analyze housing trends and predict property prices using features like location, size, and condition.

### 💡 Key Features Used:
- `sqft_living`, `bedrooms`, `bathrooms`, `zipcode`, `grade`, `condition`, etc.

### 🔍 What Was Done:
- Cleaned dataset and handled outliers  
- Explored price trends via visualization  
- Developed regression models to capture impact of multiple features  
- Regularized using Ridge & Polynomial regression for better generalization

---

## 🧰 Libraries Used

```python
pandas, numpy, seaborn, matplotlib, scikit-learn
```

---

## ✅ Outcomes

- 📈 Built robust regression models for prediction  
- 🧠 Applied feature engineering and regularization  
- 📊 Performed complete ML pipeline from raw data to evaluation  
- 🔍 Gained real-world insights from insurance and housing datasets

---

## 📬 Contact

**Anmay Kapoor**  
📧 anmaykapoor15@gmail.com  
📍 Jaipur, India  
[🔗 LinkedIn](https://www.linkedin.com/in/anmay-kapoor-b87702154)



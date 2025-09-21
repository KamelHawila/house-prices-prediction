# 🏡 House Prices Prediction – Kaggle Competition

This project is my solution to the [Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
competition.  
The goal is to predict the final sale price of homes based on 80+ features describing different aspects of residential houses.

---

## 🚀 Results
- Achieved **Top 10% (Rank 449 / 4244)** on the Kaggle leaderboard.  
- Built an end-to-end regression pipeline including **data cleaning, feature engineering, model training, and evaluation**.

---

## 📊 Project Overview
### Steps I followed:
1. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions, correlations, and missing values.  
   - Identified outliers and skewed features.

2. **Data Cleaning & Preprocessing**  
   - Handled missing values (imputation).  
   - Encoded categorical variables (OneHot, Label Encoding).  
   - Normalized numerical features.  

3. **Feature Engineering**  
   - Created domain-inspired features (e.g., `TotalSF`, `TotalBathrooms`, `PropertyAge`).  
   - Generated interaction terms and boolean flags.  

4. **Modeling**  
   - Trained multiple models: **Random Forest, XGBoost, CatBoost**.  
   - Used **cross-validation** with RMSE metric.  
   - Performed **hyperparameter tuning** with RandomizedSearchCV.  

5. **Ensembling**  
   - Combined predictions (stacking/blending).  
   - Submitted best-performing model.

---

## 🛠️ Tech Stack
- **Languages**: Python  
- **Libraries**: scikit-learn, pandas, numpy, matplotlib, seaborn, plotly, XGBoost, CatBoost  
- **Tools**: Jupyter Notebook, Git, Kaggle  

---

## 📂 Repository Structure

- **data/** → Dataset files (not included, download from Kaggle)
- **notebooks/** → Jupyter notebooks for EDA, feature engineering, and modeling
- **src/** → Python scripts (data preprocessing, feature engineering, model training)
- **submission/** → CSV submission files
- **requirements.txt** → List of dependencies
- **README.md** → Project documentation
- **.gitignore** → Ignore large files and cache


🏡 House Prices Prediction – Kaggle Competition

This project is my solution to the Kaggle House Prices: Advanced Regression Techniques competition.
The goal is to predict the final sale price of homes based on 80+ features describing various aspects of residential properties.

🚀 Results

🏆 Achieved Top 10% (Rank 449 / 4244) on the Kaggle leaderboard

🧠 Built an end-to-end regression pipeline for data cleaning, feature engineering, model training, and evaluation

📊 Project Overview
1️⃣ Exploratory Data Analysis (EDA)

Visualized feature distributions, correlations, and missing values

Identified outliers and handled skewed numerical features

2️⃣ Data Cleaning & Preprocessing

Handled missing values using imputation

Encoded categorical variables with One-Hot and Label Encoding

Scaled numerical features for better model performance

3️⃣ Feature Engineering

Created new features like TotalSF, TotalBathrooms, and PropertyAge

Generated interaction terms and boolean flags for improved learning

4️⃣ Modeling

Trained multiple algorithms: RandomForest, XGBoost, CatBoost

Evaluated models using cross-validation (RMSE)

Applied RandomizedSearchCV for hyperparameter tuning

5️⃣ Ensembling

Combined top models using stacking/blending

Selected and submitted the best performing ensemble

🛠️ Tech Stack

Languages: Python
Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, plotly, XGBoost, CatBoost
Tools: Jupyter Notebook, Git, Kaggle

📂 Repository Structure
house-prices-prediction/
│
├── data/                 # (Not included – download from Kaggle)
├── notebooks/            # Jupyter notebooks for EDA, feature engineering, modeling
├── src/                  # Python scripts (preprocessing, feature engineering, model training)
├── submission/           # CSV submission files
├── requirements.txt      # Dependencies
├── README.md             # Project documentation
└── .gitignore            # Ignore data & cache files

📦 Installation
# Clone this repository
git clone https://github.com/<your-username>/house-prices-prediction.git
cd house-prices-prediction

# Install dependencies
pip install -r requirements.txt

🧮 Usage

Run the notebook or scripts to train and evaluate the model:

jupyter notebook notebooks/Project.ipynb

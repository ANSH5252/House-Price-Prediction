# 🏠 House Prices - Advanced Regression Techniques  
This project presents a comprehensive solution to the House Prices: Advanced Regression Techniques competition on Kaggle. The goal is to predict the final price of residential homes in Ames, Iowa using advanced machine learning models and feature engineering.

## 📂 Repository Structure
```
House-Prices-Advanced-Regression-Techniques/
│
├── data_description.txt     # Info About the Features of Dataset
├── h_p_p.ipynb              # Jupyter notebooks for EDA, modeling, and evaluation
├── train.csv                # Dataset for Training Puropse
├── test.csv                 # Dataset for Test Puropse
├── sample_submission.csv    # Format of Submission
└── README.md                # Project documentation
```
##🚀 Project Highlights
- 📊 **Exploratory Data Analysis (EDA) to understand distributions, relationships, and outliers

- 🛠️ Feature Engineering including skewness handling, missing value treatment, and encoding

### 📉 **Modeling Techniques:**

- 🔹 **Linear Models:**
  - Linear Regression
  - Ridge Regression
  - Lasso / ElasticNet

- 🌳 **Ensemble Models:**
  - Random Forest Regressor
  - XGBoost Regressor

- 🧠 **Neural Networks:**
  - MLPRegressor (Multi-layer Perceptron)

- 🧱 **Stacking Ensemble:**
  - StackingRegressor with meta-learners:
    - MLP
    - XGBoost
    - Linear Regression

- ⚙️ **Pipelines & Preprocessing:**
  - ColumnTransformer
  - Pipelines with OneHotEncoder, StandardScaler, SimpleImputer

- 🔎 **Model Selection:**
  - GridSearchCV for hyperparameter tuning
  - K-Fold Cross-Validation

- 📉 **Evaluation Metrics:**
  - RMSE (Root Mean Squared Error)


## 📌 Key Techniques Used

- 📊 **Exploratory Data Analysis (EDA)**  
  - SalePrice distribution analysis  
  - Q-Q plots and normality checks  
  - Outlier detection using **IQR method**

- 🧹 **Data Preprocessing**
  - Missing value imputation using `SimpleImputer`
  - Feature scaling with `StandardScaler`
  - Categorical encoding with `OneHotEncoder`
  - Feature pipelines using `ColumnTransformer` and `Pipeline`

- 🧠 **Feature Engineering**
  - Log transformation of skewed features  
  - PCA for dimensionality reduction *(if applied)*  
  - Manual selection of important features

- 📦 **Model Training & Evaluation**
  - Training multiple models with `GridSearchCV`
  - Hyperparameter tuning with exhaustive search
  - Cross-validation using `KFold`
  - Evaluation using **Root Mean Squared Error (RMSE)**

- 🧱 **Ensemble Learning**
  - Combining models using `StackingRegressor` with multiple meta-models  
  - Meta-model tuning (MLP, XGBoost, LinearRegression)

- 📈 **Visualization**
  - Interactive plots using **Plotly** (`plotly.express`, `go.Figure`)
  - Histogram + Normal distribution overlay
  - Q-Q plots for assessing normality



## 👤 Author
Anshuman Dash  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/ANSH5252)

## 📜 License
This project is licensed under the MIT License.     


# ML-Regressor
This projects analyzes the dataset of cars with 7 features (weight, acceleration, origin, engine power, number of cylinders, year and engine displacement).

**Objective:** To predict the fuel consumption of the car, this is, the regression problem (to predict the value of a continuous variable) is adressed in this document.

## Overview
First, the exploratory data analysis (EDA) is performed to show the content of the raw dataset. Second, the data preprocessing is performed, which consist of:

a. Filling null values and dropping duplicates.

b. Processing outliers and multicollinearity.

c. Converting categorical variables into binary ones.

d. Standarizating the data.

Third, the training and validation of the performance of 5 different ML algorithms are compared. The ML models are:

• Algorithm 1: **Lasso (Linear regression with L1 regularization)**.

• Algorithm 2: **Ridge (Linear regression with L2 regularization)**.

• Algorithm 3: **DecisionTreeRegressor**.

• Algorithm 4: **RandomForestRegressor**.

• Algorithm 5: **GradientBoostingRegressor**.

• Algorithm 6: **XGBRegressor (XGBoost library)**.

• Algorithm 7: **LGBMRegressor (LightGBM library)**.

• Algorithm 8: **CatBoostRegressor (CatBoost library)**.

Finally, the best algorithim is selected for this particular dataset.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy, Scikit-learn, xgboost, lightgbm, catboost.

The Jupyter Notebook is in notebooks/regressor.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/ML-Regressor.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in notebooks/regressor.ipynb.
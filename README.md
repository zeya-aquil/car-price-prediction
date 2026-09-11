# Car Price Prediction 🚗

A beginner machine learning project that predicts the selling price of used cars using regression models.

## 📌 Project Overview

The goal of this project is to predict the selling price of a used car based on features such as:

- Year
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔄 Machine Learning Workflow

1. Data Collection
2. Data Loading
3. Data Preprocessing
4. Categorical Variable Encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Price Prediction

## 🤖 Models Used

### Linear Regression

Used as the baseline regression model.

### Lasso Regression

Used with L1 regularization and compared with Linear Regression.

## 📊 Results

| Model | R² Score |
|---|---:|
| Linear Regression | 0.8366 |
| Lasso Regression | **0.8710** |

Lasso Regression achieved the higher R² score on the test data.

## 📁 Project Files

- `car_price_prediction.ipynb` — Jupyter Notebook containing the complete analysis and ML implementation.
- `car_data.csv` — Dataset used for training and testing.

## 📚 What I Learned

Through this project, I gained practical experience with:

- Data preprocessing
- Handling categorical variables
- Train-test splitting
- Linear Regression
- Lasso Regression
- Model evaluation using R² score

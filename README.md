# 🏠 House Price Prediction using Linear Regression

This project demonstrates a **regression-based machine learning model** that predicts house prices based on various property features using **Linear Regression**.

## 📌 Objective

Build a machine learning model to predict the **price of a house** given features like square footage, number of bedrooms and bathrooms, floors, view, and more.


## 🧰 Tech Stack

- **Language**: Python
- **Libraries**: Pandas, scikit-learn, Matplotlib, Seaborn


## 🔍 Key Steps

1. **Data Cleaning & Exploration**:
   - Checked for null values and data types
   - Used `describe()` and `info()` for insights

2. **Feature Selection**:
   - Selected 8 key features for training the model

3. **Modeling**:
   - Applied **Linear Regression** using `scikit-learn`
   - Trained on 80% of the data and tested on 20%

4. **Evaluation**:
   - Calculated **Mean Squared Error (MSE)**
   - Evaluated model with **R² score**
   - Plotted **Actual vs Predicted** prices


## 📈 Results

- **R² Score**: Indicates how well the model explains the variance in price.
- **Visualization**: Scatter plot comparing actual vs predicted house prices.


## 🚀 How to Run

1. Download the dataset (e.g., from Kaggle or another source).
2. Install the necessary libraries

`pip install pandas scikit-learn matplotlib seaborn`



# task3
# 🏠 House Price Prediction - Linear Regression

This project implements both **simple and multiple linear regression** models to predict house prices using Python and scikit-learn.

---

## 🎯 Objective

- Build linear regression models using real-world housing data.
- Understand how different features like area, bedrooms, and bathrooms affect price.
- Evaluate model performance using standard metrics.
- Visualize regression results and interpret coefficients.

---

## 📁 Dataset

The dataset contains house-related features such as:
- `area`
- `bedrooms`
- `bathrooms`
- `price`

You can use any similar housing dataset (e.g., from Kaggle or open ML repositories).

---

## 🧰 Tools & Libraries Used

- **Pandas** – for data handling
- **Matplotlib** – for visualization
- **Scikit-learn** – for model building and evaluation

---

## 📊 Workflow

1. Import and preprocess the dataset (`house_price.csv`)
2. Split the data into training and testing sets
3. Fit a Linear Regression model using `sklearn.linear_model`
4. Evaluate performance using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score
5. Plot the regression line (for simple regression)
6. Interpret model coefficients and intercept

---

## 📈 Sample Output

- Regression Line Plot (for `area vs price`)
- MAE, MSE, and R² score values
- Printed model coefficients like:

# multi-Linear-Regression
# Multi-Linear Regression Implementation

A Python implementation of multi-linear regression from scratch, with optional comparison to scikit-learn's implementation.

## Features

- � Pure Python implementation of multi-linear regression algorithm
- 📈 Supports multiple independent variables (features)
- ⚖️ Includes feature scaling/normalization
- 📊 Visualization tools for regression analysis
- 🔍 Model evaluation metrics (R-squared, MSE, RMSE)
- 🆚 Comparison with scikit-learn's LinearRegression
- 📝 Jupyter notebook with detailed explanation and examples

## Requirements

- Python 3.6+
- NumPy
- pandas
- matplotlib
- scikit-learn (for comparison)
- Jupyter Notebook (for tutorial)

## Usage

```python
from multi_linear_regression import MultiLinearRegression

# Initialize and fit model
model = MultiLinearRegression()
model.fit(X_train, y_train)

# Make predictions
predictions = model.predict(X_test)

# Evaluate model
r2 = model.r_squared(X_test, y_test)  

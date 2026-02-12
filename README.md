# Linear Regression Assignment

# Student Name: YATHARTH PATHAK
# Roll No: CSJMA23001390169

# Student Name: AMAN DUBEY
# Roll No: CSJMA23001390072

# Course: Machine Learning
# Branch: B.Tech CSE-AI, 3rd Year  
# Topic: Predicting house prices using California Housing dataset  

# Objective
To perform end-to-end analysis of various Linear Regression techniques on a real-world dataset, including:
- Exploratory Data Analysis (EDA)
- Simple Linear Regression
- Multiple Linear Regression
- Polynomial Regression (degree 2)
- Regularization (Ridge and Lasso)
- Model diagnostics and performance comparison

# Dataset
Name: California Housing Dataset  
Source: scikit-learn (`fetch_california_housing`) + exported as CSV  
Target: `MedHouseVal` (median house value in $100,000s)  
Features: 8 numerical features (MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude)
# Dataset: California Housing (built-in from sklearn) 
# Date: February 2026

# Repository Contents
- `Linear_Regression_Assignment.ipynb` → Complete lab work with EDA, all models, visualizations and conclusions
- `california_housing.csv` → Dataset used
- `plots/` → Saved figures (histograms, heatmap, regression lines, residuals, etc.)
- `playground.ipynb` → Experimental / scratch notebook
- `test.ipynb` → Experimental / scratch notebook
- `README.md` → This file

# Key Highlights
- **EDA**: Histograms, correlation heatmap, outlier analysis
- **Simple LR**: Strongest single feature (`MedInc`) → regression line plot
- **Multiple LR**: All features → best overall performance
- **Polynomial LR**: Degree 2 → captures non-linearity better than simple model
- **Ridge & Lasso**: Regularization, coefficient shrinkage, feature selection insight
- **Diagnostics**: Residuals vs. predicted values, Q-Q plot
- **Evaluation metrics**: MSE, RMSE, R² score (comparison table included in notebook)

# Technologies Used
- Python
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook / Google Colab

# Key visualizations
- Histograms of features
- Correlation heatmap
- Simple regression line
- Residual diagnostics (residuals vs predicted, histogram, Q-Q plot)

# Results Snapshot
(Actual values from notebook)

| Model                      | R² Score | RMSE    | Comment                          |
|----------------------------|----------|---------|----------------------------------|
| Simple Linear Regression   | ~0.47    | ~1.15   | MedInc only                      |
| Multiple Linear Regression | ~0.60    | ~0.99   | Best performance                 |
| Polynomial (degree 2)      | ~0.53    | ~1.08   | Improved single-feature fit      |
| Ridge                      | ~0.60    | ~0.99   | Similar to OLS                   |
| Lasso                      | ~0.60    | ~0.99   | Some coefficients shrunk         |

# Main conclusion: Multiple linear regression gives the best balance of accuracy and interpretability. Median income is the dominant predictor.

**GitHub Profile**: [Yatharth007Pathak](https://github.com/Yatharth007Pathak)  

Submitted as part of the Linear Regression Lab Assignment.

# simple-Linear-Regression-only-by-using-numpy
Sales Prediction Using Advertising Data
Project Overview
This project uses simple linear regression to predict sales based on advertising expenditure. By employing Python and NumPy, the model examines the relationship between advertising budgets (independent variable) and sales performance (dependent variable). It highlights the practical application of statistical modeling and basic machine learning techniques, focusing on a single predictor.

The primary goal is to help businesses estimate sales outcomes based on advertising investments, enabling better budget allocation and ROI analysis. The project is an excellent starting point for understanding regression analysis and how it applies to real-world scenario

# Model Development
Linear Regression
The regression line is computed using NumPy’s np.polyfit function, which calculates the slope (𝑚m) and intercept (𝑏b) of the best-fit line. The regression equation is represented as:
𝑦=𝑚𝑥+𝑏
y=mx+b
where 𝑦
y is the predicted sales, 𝑚
m is the slope indicating the rate of change, and 𝑏
b is the intercept where the line crosses the y-axis.
# Visualization
Matplotlib is employed to create a scatter plot of the actual sales data points and overlay the regression line. This visual representation highlights the correlation between advertising expenditure and sales, making it easier to interpret the model's accuracy and fit.

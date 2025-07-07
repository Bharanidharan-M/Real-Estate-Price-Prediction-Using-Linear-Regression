#  Real Estate Price Prediction Using Linear Regression

This repository demonstrates a simple machine learning project where we use **Linear Regression** to predict real estate prices based on property size using Python and Scikit-learn.

##  Project Workflow

1. **Data Loading**
   - Loaded CSV file using `pandas`
   - Checked for null/missing values

2. **Exploratory Data Analysis (EDA)**
   - Plotted a scatter plot to visualize the relationship between size and price

3. **Data Preprocessing**
   - Split data into training and testing sets (80/20 split)

4. **Model Building**
   - Applied `LinearRegression` from Scikit-learn

5. **Evaluation**
   - Used metrics: R² Score, MAE, MSE, RMSE

6. **Prediction**
   - Predicted prices for new property sizes

7. **Visualization**
   - Plotted regression line and prediction results

---

##  Model Details

- **Intercept**: `96918.64`
- **Coefficient**: `228.59`



## Evaluation Metrics

| Metric              | Value       |
|---------------------|-------------|
| R² Score            | 0.836       |
| Mean Absolute Error | 28,324      |
| Mean Squared Error  | 1,080,143,288 |
| RMSE                | 32,865      |

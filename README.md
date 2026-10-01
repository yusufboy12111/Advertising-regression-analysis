# Advertising Sales Regression Analysis

A Python project implementing a Multiple Linear Regression model using **scikit-learn** to analyze and predict sales numbers based on advertising spending across TV, radio, and newspaper mediums.

## Project Framework
1. **Data Preprocessing**: Removing index columns and managing data dimensionality.
2. **Feature Matrices**: Extracting independent variable configurations (`X`) and target outputs (`y`).
3. **Data Splitting**: Segmenting arrays into independent validation states using reproducible randomized controls.
4. **Model Performance Evaluation**: Computing MAE, MSE, and \(R^2\) metrics to measure prediction deviations.
5. **Statistical Visualization**: Generating residual distribution profiles and actual-vs-predicted correlation charts.

## Technologies Used
* Python 3
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

## Evaluation Metrics Summary
The model calculates performance tracking through:
* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **R-squared (\(R^2\)) Score**

## Visualizations Included
* **Actual vs. Predicted Sales**: Features a 45-degree reference line (\(y=x\)) to evaluate absolute prediction proximity.
* **Residuals vs. Predicted Sales**: Uses a stable horizontal baseline (\(y=0\)) to isolate non-linear error distributions.

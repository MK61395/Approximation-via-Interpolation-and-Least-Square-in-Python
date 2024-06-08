# Approximation-via-Interpolation-and-Least-Square-in-Python
Performing approximation via interpolation and least square method on a dataset with 11 points using SciPy# Approximation via Interpolation and Least Squares Method

## Overview
This assignment demonstrates data approximation using two methods: interpolation and the least squares method. The objective is to approximate a dataset with 11 points and compare the accuracy of these methods using the Root Mean Squared Error (RMSE).

## Project Structure
The project consists of the following key components:

1. **Dataset Visualization**: 
    - Plotting subdatasets from Anscombe's quartet to visualize the data points.

2. **Root Mean Squared Error (RMSE)**:
    - A function to compute RMSE with higher precision, providing a measure of the approximation accuracy.

3. **Approximation via Interpolation**:
    - Using `interp1d` from SciPy to perform cubic and linear interpolation on the dataset.
    - Comparing the interpolated values with the actual data points to calculate RMSE.

4. **Approximation via Least Squares Method**:
    - Using a custom function to perform least squares approximation and determine the coefficients of the fitted polynomial.
    - Comparing the least squares fitted values with the actual data points to calculate RMSE.

## Dataset Visualization
The dataset from Anscombe's quartet is visualized using scatter plots for each subdataset. This helps in understanding the distribution and characteristics of the data points before applying approximation methods.

## Root Mean Squared Error (RMSE)
A custom function is implemented to compute the RMSE with higher precision using the `decimal` module. This ensures accurate assessment of the approximation methods.

## Approximation via Interpolation
- **Methods Used**: 
    - Cubic interpolation
    - Linear interpolation
- **Process**: 
    - The dataset is sorted and the interpolation functions (`interp1d`) are applied.
    - The interpolated values are compared with the actual values to compute the RMSE.
- **Results**:
    - RMSE for Cubic Interpolation
    - RMSE for Linear Interpolation

## Approximation via Least Squares Method
- **Process**: 
    - A custom function performs least squares approximation by constructing the design matrix and solving for the coefficients of the fitted polynomial.
    - The least squares fitted values are compared with the actual values to compute the RMSE.
- **Results**:
    - RMSE for Least Squares Approximation

## Results
The RMSE values for both interpolation (cubic and linear) and least squares methods are computed and compared. These values indicate the accuracy of each approximation method.

## Conclusion
This assignment successfully demonstrates the application of interpolation and least squares methods for data approximation. The RMSE values provide insights into the accuracy of each method, helping to understand their strengths and limitations when applied to the given dataset.




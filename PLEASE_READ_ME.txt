Conclusion: Predicting House Prices using Linear Regression

The objective of this task was to build a Linear Regression
 model to predict house prices based on selected features such 
 as number of rooms,socio-economic factors, and environmental conditions.

After performing data preprocessing, feature selection, and visualization,
a model was trained using key variables including rm, lstat, ptratio, dis,
and nox. Initial results showed moderate performance, but improvements were
achieved by applying a logarithmic transformation to the target variable (medv), 
which helped stabilize variance and improve model accuracy.

The final model achieved an R² score of approximately 0.73, indicating that about
73% of the variation in house prices is explained by the model. 
The predictions were generally close to actual values, especially for mid-range 
house prices, though slight errors were observed for higher-priced houses.

Key findings include:

The number of rooms (rm) has a strong positive influence on house prices.
The lower status population (lstat) has a strong negative impact.
Environmental and social factors such as pollution (nox) and education ratio (ptratio) 
also contribute to price variation.

In conclusion, Linear Regression proved to be an effective baseline model for
 house price prediction. However, its limitations in capturing complex, 
 non-linear relationships suggest that further improvements could be achieved 
 using advanced models such as Ridge Regression or Polynomial Regression.
## Summary 
This project analyses the Portuguese White Wine Quality dataset from the UCI Machine Learning Repository to identify which chemical properties most strongly influence wine quality ratings. Explored relationships between 11 physicochemical features and wine quality using correlation analysis, multicollinearity checks (VIF), and multiple linear regression. Feature selection was performed using exhaustive search, forward selection, and backward selection (AIC), all of which converged on the same final set of predictors. After addressing multicollinearity (by removing density), we built a regression model using 10-fold cross-validation. The model achieved reasonable predictive performance (RMSE ≈ 0.85, MAE ≈ 0.66) and explained ~28% of the variance in wine quality.

The results show that:

- Alcohol content has a strong positive relationship with wine quality

- Volatile acidity has a strong negative relationship with wine quality

- While the model is limited by the absence of sensory and environmental factors, it provides useful insights into how chemical composition impacts perceived wine quality and highlights opportunities for future improvements using richer datasets.

Techniques used:

- Data cleaning & normalisation

- Correlation analysis & VIF

- Multiple linear regression

- Model selection (AIC)

- Cross-validation

- Assumption checking (linearity, homoscedasticity, normality)

#  House Price Prediction - Linear Regression

##  Objective
Implement *Simple & Multiple Linear Regression* to predict house prices using features such as area, bedrooms, bathrooms, amenities, etc., and validate regression assumptions.

##  Dataset
The dataset contains *545 rows* and *13 columns*:

| Column | Description |
|--------|-------------|
| price | Price of the house |
| area | Total area in sq. ft |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of stories |
| mainroad | Whether connected to main road |
| guestroom | Availability of guest room |
| basement | Availability of basement |
| hotwaterheating | Availability of hot water heating |
| airconditioning | Availability of air conditioning |
| parking | Number of parking spaces |
| prefarea | Preferred area |
| furnishingstatus | Furnishing status of the house |

## 🛠 Tools Used
- *Python*
- *Pandas, **NumPy*
- *Scikit-learn*
- *Matplotlib, **Seaborn*
- *Statsmodels* (for statistical tests)

##  Steps
1. *Load and preprocess* dataset (encode categorical variables).
2. *Split* data into training & testing sets.
3. *Train* Linear Regression model.
4. *Evaluate* using MAE, MSE, RMSE, R².
5. *Check assumptions*:
   - Linearity
   - Normality of residuals
   - Multicollinearity (VIF)
   - Homoscedasticity (Breusch-Pagan Test)
6. *Interpret coefficients* to understand feature impact.

##  Evaluation Metrics
- *MAE*: Mean Absolute Error  
- *MSE*: Mean Squared Error  
- *RMSE*: Root Mean Squared Error  
- *R²*: Coefficient of Determination  

##  Key Learnings
- Building & interpreting a regression model.
- Validating regression assumptions.
- Understanding multicollinearity via VIF.

---

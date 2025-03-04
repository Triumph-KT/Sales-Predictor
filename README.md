# Sales-Predictor
Predict total sales for SuperKart’s outlets to guide business strategy, optimize inventory, and support sales operations across different city tiers.

# Dataset:
Includes product attributes (Product_Type, Product_MRP, Product_Sugar_Content) and store characteristics (Store_Size, Store_Location_City_Type) to predict Product_Store_Sales_Total.

## Methods and Workflow:
# Exploratory Analysis:
- Identified OUT004 as the top-performing store (Tier 2 city, medium size).
- Discovered that fruits, vegetables, and snack foods are top revenue generators.

# Feature Engineering:
- Added Store_Age_Years.
- Grouped products into Perishables and Non-Perishables.

# Modeling:
- Built and refined linear regression models using Ordinary Least Squares (OLS).
- Removed insignificant variables based on p-values and checked multicollinearity using VIF.

# Validated assumptions: 
- residual normality,
- homoscedasticity, and
- linearity.

# Model Performance:
- Achieved ~79% R² explaining sales variance.
- Applied 10-fold cross-validation to confirm model stability.

# Insights and Recommendations:
- Scale successful stores (like OUT004) and optimize underperformers (like OUT001).
- Maintain stock for high-revenue categories (fruits, vegetables, snacks).
- Consider demographic data and seasonal trends for future enhancements.

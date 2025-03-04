# SuperKart-Sales-Prediction

Developed a regression-based predictive model to forecast product-level sales across SuperKart stores and provide strategic recommendations for business growth and inventory management.

## Project Overview

This project forecasts product sales at SuperKart supermarkets to support business decisions on expansion, inventory management, and marketing strategies across stores in different city tiers.

## Dataset

- Product-level sales records across multiple stores with features such as:
  - Product types
  - Maximum Retail Price (MRP)
  - Store size
  - City tier
  - Product sugar content
  - Store establishment year

## Objectives

- Predict quarterly sales for products at various stores.
- Identify key factors driving sales performance.
- Recommend strategies to optimize store operations.

## Methods

- Exploratory Data Analysis (EDA).
- Feature engineering, including **store age** and **perishability categories**.
- Linear regression modeling using **Ordinary Least Squares (OLS)**.
- Multicollinearity checks with **Variance Inflation Factor (VIF)**.
- Cross-validation for model validation.

## Results

- Achieved an **R² of approximately 79%** on validation data.
- Identified top-performing stores and product categories.
- Recommended scaling successful stores and improving underperformers.
- Suggested inventory prioritization for high-revenue products.

## Business Impact

- Informed store expansion decisions.
- Improved marketing strategies for underperforming locations.
- Optimized inventory of high-demand products.

## Technologies Used

- Python
- Pandas
- Statsmodels
- Scikit-learn
- Matplotlib

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/superkart-sales-prediction.git
    ```

2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open and run the notebook to reproduce the results.

# sales-profitability-forecasting

# Comprehensive Sales and Profitability Analysis for XYZ Corporation

This project presents a detailed data-driven analysis of sales and profitability trends for a fictional retail company, XYZ Corporation. The company operates three physical stores and manages centralized product pricing. The goal is to generate actionable insights through statistical analysis and time series forecasting.

##  Project Objectives

- Merge, clean, and preprocess sales and pricing data across three stores.
- Perform distribution analysis and profitability evaluation for products and stores.
- Build predictive models to forecast future sales trends using ARIMA and SARIMA.
- Deliver strategic recommendations for inventory planning and business decision-making.

##  Data Sources

- `product_pricing_data.csv` – Contains cost and selling price of each product.
- `Store_A_sales_data.csv`, `Store_B_sales_data.csv`, `Store_C_sales_data.csv` – Daily sales records for six products per store.

## Tools & Libraries

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (Data Visualization)
- Statsmodels (ARIMA, SARIMA)
- Scikit-learn (Linear Regression)
- Jupyter Notebook

##  Key Analysis Steps

1. **Data Importation & Preprocessing**  
   - Added store identifiers, concatenated datasets, reshaped to long format.
   - Merged with pricing data and checked for missing values.

2. **Distribution Analysis**  
   - Conducted normality tests and visualized sales distributions.
   - Explored daily and product-wise sales variation.

3. **Summary Statistics**  
   - Total & average sales per product and per day across all stores.

4. **Profitability Analysis**  
   - Identified top-performing and underperforming products using cost and selling price data.

5. **Sales Forecasting**  
   - Implemented linear regression and ARIMA models.
   - Applied SARIMA for products with clear seasonality.
   - Evaluated model performance and forecast reliability.

## 📈 Forecasting Insights

- SARIMA captured strong monthly seasonality for select products.
- ARIMA models provided effective baseline forecasts for non-seasonal data.
- Forecasts helped identify declining trends and informed stock planning.

- ## Recommendations

- Align inventory with forecasted demand to avoid stockouts or surplus.
- Use seasonal promotions and pricing strategies for high-performing products.
- Apply bundling or offers to revive interest in low-turnover items.
- Continuously update models with new data to stay responsive to demand shifts.

##  Conclusion

This project demonstrates the effective use of data wrangling, visualization, statistical modeling, and forecasting to generate strategic business insights for retail operations.


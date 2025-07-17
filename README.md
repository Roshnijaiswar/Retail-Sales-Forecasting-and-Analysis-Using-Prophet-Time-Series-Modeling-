**🛒 Retail Sales Analysis**
This project analyzes historical retail sales data using time series forecasting models like ARIMA and Facebook Prophet. The goal is to identify trends, visualize category-level performance, and predict future sales.

**📁 Dataset**
The dataset used includes:

Date: Timestamp of sales

Product Category: Category of items sold

Total Amount: Total revenue/sales amount per transaction

**📊 Key Analyses Performed**
Time-based sales trend visualization

Sales breakdown by product category

Train-test split visualization

Forecasting using ARIMA and Prophet models

RMSE calculation for model performance evaluation

**🧠 Models Used**
ARIMA (AutoRegressive Integrated Moving Average)

Naive Forecast (baseline)

Prophet by Meta (for time series forecasting)

**📈 Visualizations**
Line plot of sales trend

Bar chart of sales by category

Forecast vs actual comparison

Prophet component plots (trend, weekly seasonality, etc.)

**📦 Libraries Used**
pandas

matplotlib

statsmodels

sklearn

prophet

numpy

**🛠️ How to Run**
Clone the repository

Ensure you have all dependencies installed:
bash
Copy
Edit
pip install pandas matplotlib statsmodels scikit-learn prophet
Run Retail Sales Analysis.ipynb in Jupyter Notebook

📌 Output Metrics
Root Mean Squared Error (RMSE) for both ARIMA and Prophet forecasts
Visual forecast for the next 30 days using Prophet


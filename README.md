# ✈️ Aviation KPI Dashboard - Power BI & Machine Learning

## 📌 Project Overview
This Power BI dashboard provides key insights into aviation performance metrics, focusing on **flight delays, aircraft utilization, revenue, and profitability**. It integrates **Machine Learning (ML) models** to enhance predictions for operational efficiency and financial forecasting.

## 🚀 Key Features
- **Operational Metrics:** Flight delays, turnaround time, fleet availability.
- **Financial Analysis:** Revenue, operating cost, net profit margin.
- **Performance Insights:** Load factor, fuel efficiency, maintenance downtime.
- **Dynamic Filtering:** Flight number, date range, profitability segments.
- **ML Predictions:** Flight delay forecasting, profitability estimation.
- **Interactive Visuals:** KPI cards, bar charts, heatmaps, and scatter plots.

## 📊 Data Breakdown
The dataset consists of **200,000+ records** with **18 columns**:
- **Flight Performance:** Flight number, departure times, delay minutes.
- **Operational Efficiency:** Utilization hours, turnaround time, fleet availability.
- **Financial Metrics:** Revenue, cost, net profit, debt-to-equity ratio.
- **Key Ratios:** Load factor, revenue per ASK, cost per ASK.

## 🔍 Dashboard Insights
### **1. Delay Analysis**
- Categorization: **Short (0-30 mins), Medium (31-90 mins), Long (91+ mins)**.
- ML model predicts expected delays based on flight conditions.
- Impact of turnaround time on delays.

### **2. Profitability Segmentation & Prediction**
- Flights grouped as **High (>$10K), Medium ($0-$10K), Low (<$0)** profit.
- Machine Learning predicts future profitability per flight.
- Comparison of revenue vs. operating costs.

### **3. Load Factor Optimization**
- Buckets: **Low (<60%), Medium (61-85%), High (>85%)**.
- Correlation with revenue per ASK & profitability.

## 🤖 Machine Learning Model Details
- **Algorithms Used:** XGBoost & RandomForestRegressor.
- **Target Predictions:**
  - **Flight Delay Forecasting:** Predict delay categories (Short, Medium, Long).
  - **Profitability Prediction:** Estimate revenue and cost for future flights.
- **Feature Engineering:** Removal of irrelevant columns (Flight Number, Departure Times).
- **Metrics Evaluated:** Mean Absolute Error (MAE), Mean Squared Error (MSE), R-Squared (R²).
- **Model Integration:** Predictions are exported as a CSV and visualized in Power BI.

## 🛠️ Setup Instructions
### **Power BI Dashboard**
1. **Download the dataset** and import it into Power BI.
2. **Use Power Query** to create calculated columns for:
   - Delay Categories
   - Profitability Segments
   - Load Factor Buckets
3. **Build visualizations** using bar charts, slicers, and KPI cards.
4. **Customize the report** based on business requirements.

### **Machine Learning Pipeline**
1. **Train the ML model** using `hackFinal_new.ipynb`.
2. **Generate Predictions** for flight delays and profitability.
3. **Export Results** as CSV.
4. **Import Predictions into Power BI** for visualization.

## 📸 Screenshots
*(Add Power BI dashboard screenshots here)*

## 📢 Feedback & Contributions
Feel free to **fork this project** and suggest improvements! 🚀



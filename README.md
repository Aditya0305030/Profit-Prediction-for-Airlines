# ✈️ Aviation KPI Dashboard - Power BI & Machine Learning

## 📌 Project Overview
This project is a **data-driven aviation analytics dashboard** built using **Power BI and Machine Learning (ML)**. It provides insights into **flight delays, operational efficiency, profitability, and financial forecasting**. The ML models predict **flight delays** and **profitability trends**, helping airlines optimize operations and revenue strategies.

---

## 🎥 Quick Video Preview
>[Click here to watch a video demo](https://drive.google.com/file/d/1G5MvmnAMsvTS1VBrIzGVAeWNShrAP3a7/view?usp=sharing)

---

## 🚀 Key Features
✅ **Real-Time Aviation Performance Metrics** – Track flight delays, turnaround efficiency, and fleet availability.  
✅ **Financial Analysis & Profitability Forecasting** – Understand revenue, operating cost, and net profit margins.  
✅ **AI-Powered Delay & Profitability Predictions** – Leverage ML models to forecast delays and revenue trends.  
✅ **Customizable Data Filters & Slicers** – Filter by flight number, date range, profitability, and delay categories.  
✅ **Intuitive Visualizations** – Interactive KPI cards, heatmaps, bar charts, and scatter plots.  

---

## 📊 Data Breakdown
The dataset includes **200,000+ records** with **18 key aviation metrics**, categorized as:

### **1. Flight Performance Metrics**
- Flight Number
- Scheduled vs. Actual Departure Time
- Delay in Minutes
- Aircraft Utilization (Hours)
- Turnaround Time
- Fleet Availability (%)

### **2. Financial & Operational KPIs**
- Total Revenue (USD)
- Operating Cost (USD)
- Net Profit Margin (%)
- Revenue per Available Seat Kilometer (ASK)
- Cost per Available Seat Kilometer (ASK)

### **3. Load Factor & Efficiency Metrics**
- Passenger Load Factor (%)
- Fuel Efficiency Ratio
- Maintenance Downtime (Hours)

---

## 🔍 Dashboard Insights
### **1. Delay Analysis & Prediction**
- **Delay Categories:** Short (0-30 mins), Medium (31-90 mins), Long (91+ mins).
- **Seasonal & Time-of-Day Delay Trends** (Heatmaps & Line Charts).
- **ML Model Forecasts Delays Based on Flight Conditions.**

### **2. Profitability Segmentation & Prediction**
- **Profitability Segments:**
  - **High Profit:** Profit > $10,000
  - **Medium Profit:** Profit between $0 and $10,000
  - **Low Profit (or Loss-Making Flights):** Profit < $0
- **ML Model Predicts Future Profitability Per Flight.**
- **Comparison of Revenue vs. Operating Costs.**

### **3. Load Factor Optimization**
- **Load Factor Buckets:**
  - **Low (<60%)** → Underutilized flights.
  - **Medium (61-85%)** → Moderate efficiency.
  - **High (>85%)** → Optimized revenue potential.
- **Correlation Between Load Factor & Profitability.**

---

## 🤖 Machine Learning Model Details
### **ML Models Used:**
- **XGBoost & RandomForestRegressor** for regression-based predictions.
- **Target Predictions:**
  - **Flight Delay Forecasting** (Predicts delay categories based on historical flight data.)
  - **Profitability Estimation** (Predicts revenue and cost trends for upcoming flights.)

### **Feature Engineering:**
- Removal of irrelevant columns (e.g., Flight Number, Departure Times).
- Creation of new calculated fields (e.g., Delay Categories, Load Factor Buckets).

### **Model Performance Evaluation:**
- **Metrics Used:**
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-Squared (R²)
- **Exported Predictions**: Final outputs are saved as CSV and integrated into Power BI for visualization.

---

## 🛠️ Setup Instructions
### **Power BI Dashboard Setup**
1. **Import the dataset into Power BI.**
2. **Use Power Query to create calculated columns for:**
   - Delay Categories
   - Profitability Segments
   - Load Factor Buckets
3. **Build visualizations** using KPI cards, bar charts, and interactive slicers.
4. **Customize the report** based on business requirements.

### **Machine Learning Model Execution**
1. **Run the `Prediction code.ipynb` notebook to train the model.**
2. **Generate Predictions for Flight Delays & Profitability.**
3. **Export Predictions to CSV.**
4. **Load Predictions into Power BI for Insights.**

---

## 🎤 Group Presentation & Contributions
### **Project Team Members:**
👤 **[Member 1 Shivangi Rai]** – Data Scientist & ML Model Developer.  
👤 **[Member 2 Aditya]** – Power BI Developer & Dashboard Designer.  
👤 **[Member 3 Ritika Chavhan]** – Data Engineer & Feature Engineering Specialist.  

### **Presentation Structure:**
1. **Introduction:** Project overview, objectives, and team roles.
2. **Dataset Explanation:** Key features, KPIs, and structure.
3. **Power BI Dashboard Walkthrough:** KPI analysis and insights.
4. **Machine Learning Implementation:** Delay & profitability prediction models.

---
#Google Drive Link containing:
1.Video Presentation
2.Dashboard
3.PPT
4.Code
https://drive.google.com/drive/folders/12e5pKhgBDBSwIz2J-sJ-EeVVAOr_-7lD?usp=drive_link

## 📸 Screenshots
*(Insert Power BI Dashboard screenshots here)*

---
---

## 📊 Example Dashboard Screenshot
<img src="Image/Dashboard pic.png" alt="Dasboard" width='600'>

---

## 📢 Contributing
Contributions are welcome! If you'd like to enhance the project, follow these steps:
1. Fork the repository 📌
2. Create a feature branch 🚀
3. Commit your changes 📝
4. Submit a pull request 🔄

---

## ✉️ Feedback
We'd love to hear from you!

---

## 👨‍💻 Author
- [Aditya](https://github.com/Aditya0305030)
- [Ritika Chavhan](https://github.com/Ritika-Chavhan)
- [Shivangi Rai](https://github.com/shivangirai0922)

---

## 🤝 Acknowledgments
This project is made possible with:
- **Datasets**: Publicly available Aviation datasets.
- **Visualization Libraries**: Power Bi and more.

---

⭐ *Star this repository if you found it useful!* ⭐

# 📊 SalesSense – E2E Sales Forecasting and Dashboard

**Powered by Python (Prophet) + Tableau**  
*A predictive sales intelligence solution combining machine learning with business dashboarding.*

---

## 🚀 Overview

**SalesSense** enables data-driven sales strategy through:

- 📉 Analysis of historical sales trends  
- 🔮 Accurate forecasting using Facebook Prophet  
- 📊 Interactive Tableau dashboards for stakeholder decisions

**Forecast Accuracy**:  
- **MAPE**: 14.13% (business-usable accuracy)  
- **RMSE**: 6762.71  

> This project is ideal for companies seeking **inventory optimization**, **seasonal planning**, and **marketing alignment**.

---

## 🛠 Tech Stack

| Layer              | Tools / Libraries                |
|-------------------|----------------------------------|
| **Forecast Modeling** | Python, Prophet, Pandas           |
| **Visualization**      | Tableau Desktop, Tableau Story    |
| **IDE/Environment**    | JupyterLab                       |

---

## 📈 Python Workflow – Forecasting with Prophet

Using **Facebook Prophet** for its interpretability and robustness in time series modeling.

### 🔧 Key Steps:
1. **Data Cleaning & Transformation**
   - Converted dates to datetime format
   - Aggregated daily/weekly sales
   - Renamed columns for Prophet (`ds`, `y`)
   - Handled missing/null entries

2. **Modeling**
   - Applied default Prophet model with yearly seasonality
   - Tuned changepoint parameters
   - Generated 90-day forecast

3. **Output**
   - Forecast values: `yhat`
   - Uncertainty bounds: `yhat_lower`, `yhat_upper`
   - Evaluated performance:  
     - ✅ **MAPE**: 14.13%  
     - ✅ **RMSE**: 6762.71  

4. **Export for Dashboarding**
   - Final forecast and historicals saved to `.csv`
   - Used as a data source in Tableau

---

## 📊 Strategic Insights Derived

| Insight | Impact |
|--------|--------|
| **📈 Q2 2019 Sales Spike Forecasted** | Ramping up marketing and inventory can capture peak demand. |
| **📉 2018 Sales Dip Observed** | Signals a need for root-cause analysis (pricing, competition, etc). |
| **📆 Q3 as Consistent High Performer** | Focus campaigns and resources around this seasonal window. |
| **🎯 Reliable Short-Term Planning** | A MAPE of ~14% supports tactical decision-making for the next quarter. |

---

## 📍 Tableau Dashboard Highlights

**Dashboard Views Include**:
- Actual vs Forecasted Sales (Line + CI)
- Year-over-Year Trend
- Seasonal Decomposition View
- Monthly Contribution Analysis

> The final interactive dashboard helps stakeholders explore trends, trust forecasts, and **take action**.

📷(![Forecast Screenshot](https://github.com/YourUsername/YourRepoName/blob/main/forecast_plot.png?raw=true)
📷https://github.com/IyerShashank-Data/SalesSense-E2E-Sales-Forecasting-and-Dashboard/blob/main/Insights.png?raw=true
📷https://github.com/IyerShashank-Data/SalesSense-E2E-Sales-Forecasting-and-Dashboard/blob/main/Bar%20chart.png?raw=true


---

## 💼 Business Value

SalesSense isn't just a model — it's a **decision-support system**:

- Align inventory and staffing to upcoming demand
- Plan campaigns for seasonal spikes
- Investigate past dips and mitigate future risks
- Translate forecasts into **actionable strategies**

---

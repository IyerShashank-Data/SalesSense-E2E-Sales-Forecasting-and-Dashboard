# SalesSense-E2E-Sales-Forecasting-and-Dashboard

**Powered by Python (Prophet) + Tableau**

*A predictive sales intelligence project that blends machine-learning forecasts with interactive data-storytelling.*

---

## 🚀 Project Overview
**SalesSense** helps stakeholders look back, look ahead, and act:

* Analyze historical sales trends  
* Forecast future sales with confidence intervals  
* Surface clear, actionable insights for inventory, staffing, and marketing

Forecast accuracy: **MAPE ≈ 14 %** (good for business-level planning).

---

## 🛠 Tech Stack
| Layer | Tools / Libraries |
|-------|------------------|
| **Data & Modeling** | `pandas`, `prophet` (Python) |
| **Visualization** | Tableau Desktop & Tableau Story |
| **Extras** | JupyterLab |

---

## 🧠 Python Work (Forecasting with Prophet)

I used **Facebook Prophet**, a robust time series forecasting library, to generate reliable sales predictions.

### 🔧 Steps Performed in Python:
1. **Data Preprocessing**
   - Converted datetime columns
   - Aggregated daily/weekly sales totals
   - Renamed columns to match Prophet’s format (`ds`, `y`)
   - Handled missing values

2. **Model Training**
   - Used Prophet’s default configuration with trend and seasonality
   - Tuned parameters for better fit
   - Generated 3 month future dataframe

3. **Forecast Generation**
   - Output includes:
     - `yhat` (forecasted value)
     - `yhat_lower`, `yhat_upper` (confidence interval)
   - Exported the final DataFrame to CSV for Tableau use

4. **Accuracy Evaluation**
   - Calculated metrics:
     - **MAPE**: 14.13%  
     - **RMSE**: 6762.71
   - Plotted actual vs predicted to validate performance

  ## 📌 Strategic Insights

- 📈 **Q2 2019 Sales Spike Expected**  
  The forecast suggests a strong upward trend in Q2 2019. This is a key opportunity to plan ahead — increase inventory, ramp up marketing, and prepare operations for high demand.

- 📉 **2018 Performance Dip Needs Review**  
  A noticeable drop in 2018 sales indicates a potential issue. This may relate to pricing changes, customer churn, or market shifts. Deeper analysis is recommended.

- 📊 **Q3 is a Seasonal High Point**  
  Historically, Q3 shows consistent sales strength. This can guide seasonal campaign planning and budget allocations.

- 🎯 **Forecast Accuracy is Business-Ready**  
  With a MAPE of ~14%, the model is reliable enough to support real-world planning decisions — especially short-term strategy.

> These insights turn raw forecasts into business value, helping teams plan smarter and act faster.


> The final dataset was loaded into Tableau to visualize actuals, forecasts, and confidence intervals interactively.

---

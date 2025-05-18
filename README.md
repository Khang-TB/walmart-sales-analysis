# Walmart Sales Performance and Demand Seasonality Dashboard

![Header](images/Sales%20overview.png)
![Header](images/Sales%20analysis.png)
> **Interactive Power BI report that surfaces revenue drivers and seasonal patterns across 45 Walmart stores (2010 – 2012)**  
> Built for portfolio display and insight storytelling; allows anyone to refresh with the original Kaggle dataset and explore the findings in real time.

---

## 🚀 Project Goals
This repository contains a **Power BI dashboard plus a concise set of strategic recommendations** derived from historical Walmart weekly-sales data.

* Track total and year-to-date (YTD) sales, year-over-year (YoY) growth and store-level performance.  
* Identify key macro-economic and holiday factors that influence weekly revenue.  
* Pinpoint top / bottom contributing stores and quantify holiday uplift to optimise inventory and promotions.

---

## 📂 Dataset
| Field | Description |
|-------|-------------|
| `Store` | Store ID (1 – 45) |
| `Date`  | Week-ending date (MM/DD/YYYY) |
| `Weekly_Sales` | Total sales for the given store & week |
| `Holiday_Flag` | **1** if the week includes a major holiday (Super Bowl, Labor Day, Thanksgiving, Christmas); else **0** |
| `Temperature` (°F) | Average weekly temperature in the region |
| `Fuel_Price` ($) | Weekly average fuel price in the region |
| `CPI` | Consumer Price Index |
| `Unemployment` | Unemployment rate |

---

## ✨ Key Insights & Recommended Actions
| Theme | Insight | Suggested Action |
|-------|---------|------------------|
| **Seasonality** | Q4 is the strongest quarter every year; December alone is **+30 – 60 % QoQ** vs November. | Front-load seasonal inventory; boost December promotions. Launch “New Year” campaigns in **Jan – Mar** to soften the Q1 slump. |
| **Store Concentration** | **Top 14 %** of stores drive **30 %** of annual sales; bottom 32 % contribute just **16 %**. | Prioritise high-performers with exclusive SKUs & inventory; deploy training & local promos to uplift the tail. |
| **Holiday Powerhouse** | **Thanksgiving** yields the highest weekly revenue, followed by Christmas. | Ensure adequate stock & marketing for both holidays in Q4. |
| **Uplift Outliers** | Stores **7** & **35** enjoy considerably higher holiday uplift. | Investigate best practices at these locations and replicate chain-wide. |
| **Pricing Strategy** | Sales correlate (negatively) with unemployment, temperature and CPI; slight positive impact from fuel price & holiday flag. | Implement **dynamic pricing** that adapts to macro-economic shifts. |

---

## 🖼️ Dashboard Walk-Through
The report contains two core pages, each with a companion *insight* page. Screenshots are embedded in the following order:

1. **Sales Overview** – high-level KPIs, QoQ trend, treemap by store  
   ![Overview](images/Sales%20overview.png)
2. **Seasonality & Concentration** – narrative slides generated from page 1  
   ![Insights 1](images/Sales%20overview%20insights.png)
3. **Sales Analysis** – key-driver visuals, correlations, holiday uplift  
   ![Analysis](images/Sales%20analysis.png)
4. **Holiday / Uplift / Pricing** – narrative slides generated from page 3  
   ![Insights 2](images/Sales%20analysis%20insights.png)

---

## 🗂️ Repository Structure
<pre> .walmart-sales-analysis/
├── Walmart Demand Forecast.pbix         # Interactive Power BI dashboard
├── Walmart.csv                          # Raw dataset (from Kaggle)
├── README.md                            # Project overview and insights (this file)
└── images/                              # Dashboard screenshots for README
    ├── Sales overview.png
    ├── Sales overview insights.png
    ├── Sales analysis.png
    └── Sales analysis insights.png </pre>
---

## 👤 Contact

**Trương Bảo Khang**  
Email: truongbaokhang.work@gmail.com  
University: Foreign Trade University  
Major: International Economics  

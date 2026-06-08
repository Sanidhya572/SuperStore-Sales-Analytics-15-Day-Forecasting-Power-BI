# 🛒 SuperStore Sales Analytics & 15-Day Forecasting — Power BI

<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Forecasting-FF6B6B?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel/CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</p>

A 5-page interactive Power BI report built on **5,901 US retail transactions** from 2019–2020. The report delivers a complete picture of superstore performance — total sales of **$1.57M**, profit of **$175.3K**, across 4 regions, 3 product categories, and 3 customer segments — and extends into a **15-day forward sales forecast** powered by Power BI's built-in time-series intelligence.

---

## 📸 Dashboard Preview

### 🔹 Main Sales Dashboard
![Sales Dashboard](./Sales_Dashboard.png)

### 🔹 Sales By Region, Segment & Payment Mode
![Sales By Region Segment and Payment Mode](./Sales_By_Region_Segment_and_Payement_Mode.png)

### 🔹 Profit By Month and Year
![Profit By Month and Year](./Profit_By_Month_and_Year.png)

### 🔹 Sales By Month and Year
![Sales By Month and Year](./Sales_By_Month_and_Year.png)

### 🔹 15-Day Sales Forecast
![Sales Forecasting](./Sales_Forecasting.png)

---

## 🔢 Key KPIs at a Glance

| Metric | Value |
|---|---|
| 💰 Total Sales | $1,565,804 (~$1.57M) |
| 📈 Total Profit | $175,262 (~$175.3K) |
| 📦 Total Quantity Sold | 22,317 units |
| 📊 Profit Margin | ~11.19% |
| 🗓️ Data Period | Jan 2019 – Dec 2020 |
| 🗺️ States Covered | 49 US States |
| 📋 Total Orders (Rows) | 5,901 transactions |

---

## 📋 Dashboard Pages

| Page | Description |
|---|---|
| **1. Sales Dashboard** | Master overview — KPIs, category/sub-category breakdown, ship mode, state-level map, and YoY trend charts |
| **2. Sales By Region, Segment & Payment Mode** | Three donut charts showing how sales are split by geography, customer type, and payment method |
| **3. Profit By Month and Year** | YoY profit trend (2019 vs 2020) across all 12 months |
| **4. Sales By Month and Year** | YoY sales trend (2019 vs 2020) across all 12 months |
| **5. Sales Forecasting** | 15-day forward sales forecast using Power BI's built-in time-series model on daily order data |

---

## 📊 Visuals & Charts

### Page 1 — Sales Dashboard

**KPI Cards**
Three headline cards showing Total Sales ($1.57M), Total Profit ($175.3K), and Total Quantity (22K), dynamically filtered by a region slicer (Central · East · South · West).

**Sales by Segment — Donut Chart**
| Segment | Share |
|---|---|
| Consumer | 48.09% |
| Corporate | 32.55% |
| Home Office | 19.35% |

**Sales by Payment Mode — Donut Chart**
| Payment Mode | Share |
|---|---|
| COD (Cash on Delivery) | 42.62% |
| Online | 35.38% |
| Cards | 21.99% |

**Sales By Category — Bar Chart**
Office Supplies leads followed by Technology and Furniture — ranked by total revenue contribution.

**Sales By Sub-Category — Bar Chart (Top 5)**
Phones · Chairs · Binders · Storage · Accessories — the five highest-grossing product sub-categories.

**Sales By Ship Mode — Bar Chart**
Standard Class dominates, followed by Second Class, First Class, and Same Day — indicating strong customer preference for economy shipping.

**Sales and Profit by State — Map Visual**
Bubble map across 49 US states, with bubble size representing sales volume, enabling quick identification of high-revenue geographies.

---

### Page 2 — Sales By Region, Segment & Payment Mode

**Sales by Region — Donut Chart**
| Region | Sales Share |
|---|---|
| West | 33.37% |
| East | 28.75% |
| Central | 21.78% |
| South | 16.10% |

All three donut charts (Region, Segment, Payment Mode) respond dynamically to the region slicer (Central · East · South · West).

---

### Page 3 — Profit By Month and Year

Area chart overlaying 2019 and 2020 monthly profit. 2020 significantly outperforms 2019 across most months, with notable peaks in March (~$14K), October (~$15K), and December (~$17K+). Both years show consistent Q1 weakness and Q4 strength.

---

### Page 4 — Sales By Month and Year

Area chart comparing 2019 and 2020 monthly sales. 2020 shows a steep upward trajectory through H2, with December 2020 reaching the highest monthly sales (~$175K). 2019 remained comparatively flat, oscillating between ~$15K and ~$80K across the year.

---

### Page 5 — Sales Forecasting (15 Days)

- **Top panel:** Full historical daily sales trend from Jan 2019 to Dec 2020, showing cyclical demand patterns and peaks up to ~$10K/day
- **Bottom panel:** Zoomed forecast view using Power BI's built-in time-series forecasting — projects the next 15 days from the end of Dec 2020 into Jan 2021, with daily demand estimated around ~$3K based on recent trend momentum

---

## 💡 Key Insights

**1. Sales surged significantly from 2019 to 2020**
2020 sales volume nearly doubled 2019 in H2, particularly from September onwards — pointing to strong demand growth and potentially expanded customer base or product range.

**2. Q4 is the highest-performing quarter every year**
Both 2019 and 2020 show peak profit and sales in October–December, making Q4 the most critical planning window for inventory, staffing, and marketing spend.

**3. Cash on Delivery (COD) dominates at 42.62%**
The most common payment method, revealing a strong customer preference for pay-on-delivery — an important consideration for working capital and cash flow management.

**4. West region drives the highest sales at 33.37%**
The West is the top-performing region, followed by East (28.75%). South (16.10%) has the lowest share and represents the biggest untapped growth opportunity.

**5. Consumer segment is nearly half the business**
At 48.09% of sales, Consumers are the dominant customer type — almost equal to Corporate and Home Office combined.

**6. Standard Class shipping accounts for the vast majority of orders**
The dominance of economy shipping confirms that cost sensitivity is high across the customer base. Same Day delivery has minimal uptake.

**7. Phones and Chairs are the top revenue sub-categories**
These two sub-categories consistently lead by sales volume, making them the highest-priority SKUs for inventory and promotional strategy.

**8. Profit margin is ~11.19% overall**
While revenue is strong at $1.57M, the 11.19% margin leaves room for cost optimization — particularly across Furniture, which typically runs lower margins than Technology.

---

## 🗂️ Dataset Overview

**Source:** Sample SuperStore Sales Dataset (US Retail)
**Records:** 5,901 transactions · **Features:** 21 columns (post-cleanup)
**Period:** January 2019 – December 2020 · **Geography:** 49 US States

| Category | Columns |
|---|---|
| Order Info | Row ID, Order ID, Order Date, Ship Date |
| Customer Info | Customer ID, Customer Name, Segment |
| Geography | Country, City, State, Region |
| Product Info | Product ID, Category, Sub-Category, Product Name |
| Financials | Sales, Quantity, Profit |
| Operations | Ship Mode, Payment Mode, Returns |

---

## ⚙️ DAX Measures Used

```dax
-- Total Sales
Total Sales = SUM('SuperStore_Sales'[Sales])

-- Total Profit
Total Profit = SUM('SuperStore_Sales'[Profit])

-- Profit Margin %
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0) * 100

-- Total Quantity
Total Quantity = SUM('SuperStore_Sales'[Quantity])

-- Sales YoY (used in trend charts with Year field from date table)
-- Achieved via a calculated Date table using CALENDAR() and YEAR()/MONTH() columns
-- allowing the area charts to split by Year as a legend field
```

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, data modeling, all visualizations |
| **DAX** | Custom KPI measures and calculated columns |
| **Power Query (M)** | Data cleaning, type correction, column removal |
| **Power BI Forecasting** | Built-in time-series model for 15-day prediction |
| **Bing Maps (Power BI)** | State-level sales and profit bubble map |
| **Excel / CSV** | Source data format |

---

## 📁 File Structure

```
SuperStore-Sales-Analytics-15-Day-Forecasting-Power-BI/
│
├── Sales_Dashboard.pbix                              # Power BI report file (5 pages)
├── SuperStore_Sales_Dataset.csv                      # Primary data source (5,901 rows)
├── SuperStoreSales.xlsx                              # Excel version of dataset
│
├── Sales_Dashboard.png                               # Page 1 — Main Dashboard
├── Sales_By_Region_Segment_and_Payement_Mode.png     # Page 2 — Region/Segment/Payment
├── Profit_By_Month_and_Year.png                      # Page 3 — Profit Trend
├── Sales_By_Month_and_Year.png                       # Page 4 — Sales Trend
├── Sales_Forecasting.png                             # Page 5 — 15-Day Forecast
│
└── README.md                                         # Project documentation
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Sales_Dashboard.pbix` in **Power BI Desktop**
3. If prompted, reconnect the data source to `SuperStore_Sales_Dataset.csv`
4. Use the **region slicer** (Central / East / South / West) to filter all visuals dynamically
5. Navigate across all 5 report pages using the tabs at the bottom
6. On the **Sales Forecasting** page, use the slider to zoom into the forecast window

---

## 👤 Author

**Sanidhya Rajguru** — Data Analyst | Power BI Developer | MIS Analyst

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white)](YOUR_PORTFOLIO_URL_HERE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL_HERE)
[![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sanidhya572)

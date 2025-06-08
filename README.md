# Manufacturing Performance Dashboard  
*Official Submission – Emerson x DAPH National Data Challenge 2025*


![Dashboard Overview](images/Shopify_Analysis_Dashboard.png)
![Dashboard Overview](images/Details Dashboard.png)

A Power BI report built to analyze and improve manufacturing line performance through real-time insights.  
This is my first Power BI competition, and I'm proud to present a dashboard focused on identifying key production bottlenecks and operator performance issues.

---

## ✨ Dashboard Overview

| Section | Description |
|---------|-------------|
| **Single Big Numbers (SBNs)** | Displays key metrics at a glance: Total Downtime, Line Efficiency, Current Production Rate, Target Production Time, and Target Production Rate. |
| **Operator Analysis** | Focuses on individual operator downtime and efficiency to spot performance gaps. |
| **Downtime Analysis (RCA) ** | Root cause breakdown: identifies major downtime drivers by type, product, and operator. |
| **Current vs Target** | Compares actual production metrics vs. the 80% efficiency goal to track progress. |

---

---

## 📊 Main KPIs
🕒 Total Downtime (min):
How much production time was lost due to various issues.

⚙️ Line Efficiency (%):
Measures how efficiently the production line runs compared to its ideal performance (target is 80%).

📈 Current Production Rate:
Actual output rate of the line based on current performance.

🎯 Target Production Rate:
Output rate required to meet the 80% efficiency goal.

⏱️ Target Production Time:
Estimated production time needed if the line runs at 80% efficiency.

👷 Operator Downtime (by operator error):
Total downtime attributed to operator-related issues per person.

💪 Operator Efficiency:
How well each operator performs, factoring in time and output.

📦 Product Downtime:
Highlights which products experienced the most downtime—key for identifying problematic SKUs or production processes.

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Data modeling, Transformation visualizations |
| **DAX** | Custom measures (efficiency %, downtime calculations) |
| **Excel Workbook** | Extracted Data Source

---

## 🔥 Key Insights

1. **Batch Change** and **Machine Adjustment** are the leading causes of operator-related downtime.
2. **CO 600** has the highest downtime among products—suggesting a need for process review.
3. Operators **Mac**, **Charlie**, and **Dennis** are key contributors to top downtime factors.
4. Closing the gap to the **80% efficiency target** requires reducing downtime by up to **494 minutes** per batch cycle.

---

## 🙌 Acknowledgements

Huge thanks to:
- **DataSense Analytics** – for the free Power BI training and mentorship  
- **Emerson Manila** and **Data Analytics Philippines** – for organizing this inspiring event

---

can you get this inspiration and fix this below 
# Shopify Performance Dashboard

> **TL;DR** – An interactive Power BI solution that turns ~10 k rows of Shopify data into a razor-sharp command center for revenue, customers, and retention.

---

## 1 • Purpose

Cut through the noise. This dashboard isolates **Transactional Performance**, **Customer Purchase Behavior**, and **Retention & Value KPIs** so stakeholders see exactly what drives profit – and nothing else.

---

## 2 • Core KPIs

| Revenue & Volume | Customer Mix | Value & Loyalty |
|------------------|--------------|-----------------|
| **Net Sales** | **Total Customers** | **Lifetime Value** |
| **Total Quantity** | **Single-Order Customers** | **Repeat Rate** |
| **Net Avg Order Value** | **Repeat Customers** | **Purchase History Depth** |

---

## 3 • Key Interactions

| Feature | What It Does | Why It Matters |
|---------|--------------|----------------|
| **Regional Overview** | Click a province or city on the U.S. map to auto-filter every visual (KPIs, tables, trends) for that location. | Pinpoints high-performing markets or problem areas in seconds. |
| **Time-Series Trend** | Net Sales trending by **hour** and **day** with dynamic granularity toggle. | Exposes precise sales surges and dead zones for smarter promo timing. |
| **Payment Gateway Split** | Slice Net Sales by gateway (Shopify Payments, PayPal, Gift Card, etc.). | Reveals which channels convert best and where fees eat margin. |
| **Drill-Through to Detail** | Right-click any chart element to open a detail tab; export the filtered records to CSV. | Gives analysts and execs instant, clean data pulls—no SQL needed. |
| **Product-Type Lens** | Net Sales ranked by Product Type with ABC Pareto shading. | Spot product lines that punch above (or below) their weight. |

---

## 4 • Live Preview

> ![Dashboard Screenshot](images/dashboard-preview.png)  
> *Replace with your actual PNG or GIF.*

### Video Walkthrough  
🎥 **[Watch the 3-Minute Demo](https://youtu.be/your-video-link)** *(swap in your link)*

---

## 5 • How It Works

1. **Extract** – Raw Shopify CSV exports (Orders, Customers, Products).  
2. **Transform** – Power Query cleans, normalizes, and stitches tables.  
3. **Model** – Star-schema in Power BI; DAX measures for every KPI above.  
4. **Visualize** – Custom map visuals, dynamic tooltips, drill-through tabs.

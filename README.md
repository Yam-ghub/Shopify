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
5. **Refresh** – Scheduled in Power BI Service; no manual touch required.

Folder layout:



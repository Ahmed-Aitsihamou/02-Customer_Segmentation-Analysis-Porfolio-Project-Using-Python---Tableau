# 🧼 Customer Segmentation Analysis – OJAR Perfume Brand

## 📌 Project Overview

This project analyzes customer purchase behavior for **OJAR**, a premium fragrance brand, to improve marketing ROI through **RFM segmentation** (Recency, Frequency, Monetary). The result is a strategic breakdown of customer segments that informs targeting, loyalty programs, and reactivation campaigns.

---

## 🎯 Project Objective
To segment OJAR's customer base using behavioral data (purchase history) to enable personalized marketing campaigns. The goal is to identify key customer groups such as:
•	High spenders (VIPs)
•	Recent but infrequent buyers
•	Loyal repeat customers
•	At-risk or inactive customers
•	One-time buyers
These segments will guide targeted outreach, upselling, and reactivation strategies.

---

## 🗂️ Data Sources

- `ojar_transactions_table.csv`: Contains historical transaction records (customer ID, order date, product, category).
- `ojar_product_catalog.csv`: Provides product-level pricing and category info.

---

## 🧠 Methodology

### 1. Data Preparation
- Merged transaction and product data.
- Cleaned records with missing prices.
- Converted date columns for time-based analysis.

### 2. RFM Metric Calculation
- **Recency**: Days since last purchase.
- **Frequency**: Number of unique orders.
- **Monetary**: Total customer spend.

### 3. Scoring and Segmentation
- Assigned scores (1–5) for each RFM metric using quantiles.
- Combined scores into customer segments:
  - Champions
  - Loyal Customers
  - Potential Loyalists
  - Recent Customers
  - At Risk
  - Lost
  - Need Attention
  - Others

---

## 📊 Deliverables

- `ojar_rfm_customers.csv`: Cleaned dataset with full RFM scores and customer segments.
- `ojar_segment_summary.csv`: Summary of segments with customer count and average spend.
- 📈 PowerPoint Presentation: Professional insights and strategy summary for stakeholders.

---

## 🛠️ Tech Stack

- Python (pandas, datetime)
- PowerPoint (python-pptx for slide automation)
- CSV for export-ready deliverables

---

## 📁 Folder Structure

| File | Description |
|------|-------------|
| `01 - Customer Segmentation for OJAR (Perfume Brand) Requirements` | Requirement Doc |
| `02 - OJAR Datasets` | dataset |
| `03 - Python` | Complete analysis in Python |
| `04 - Presentation` | Presentation |


---

## 🎯 Business Outcomes

- Identified high-value segments (Champions, Loyal Customers) for retention focus.
- Created actionable plans for reactivating at-risk and lost segments.
- Built a foundation for personalized campaign deployment based on customer behavior.



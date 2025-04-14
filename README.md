# 🧴 OJAR Customer Segmentation – RFM Analysis

This project performs customer segmentation for **OJAR**, a premium fragrance brand, using **RFM (Recency, Frequency, Monetary)** analysis to enable targeted marketing campaigns and improve customer retention and engagement.

---

## 📊 Objective

Segment OJAR's customer base into meaningful groups such as:
- High-Value Champions
- Loyal Customers
- At-Risk Customers
- One-Time Buyers
- Potential Loyalists

This allows for strategic targeting, upselling, and reactivation campaigns.
---

## 🧠 Methodology

1. **Data Sources:**
   - Customer Transactions (CSV)
   - Product Catalog with Pricing (CSV)

2. **Steps:**
   - Merge transaction and catalog data
   - Calculate RFM metrics:
     - **Recency**: Days since last purchase
     - **Frequency**: Number of purchases
     - **Monetary**: Total spend
   - Score RFM values (1 to 5)
   - Create composite `RFM_Score`
   - Segment customers based on scoring rules

---

## 🗂️ Data Sources

- `ojar_transactions_table.csv`: Contains historical transaction records (customer ID, order date, product, category).
- `ojar_product_catalog.csv`: Provides product-level pricing and category info.

---

## 📈 Deliverables
•	Cleaned and transformed customer-level dataset with RFM scores and segments
•	Key visualizations: segment distribution, spend patterns, segment behavior
•	Dashboard in Power BI/Tableau for stakeholder insights
•	Strategic recommendations for targeted campaigns per segment


---

## 🛠️ Tools & Technologies

- Python (pandas, NumPy, seaborn, matplotlib)
- Power BI / Tableau (for dashboards)
- Google Slides for presentation

---

## 📁 Files

| File | Description | Link |
|------|-------------|------|
| `01 - Customer Segmentation for OJAR (Perfume Brand) Requirements` | Requirement Doc | [Link]() |
| `02 - OJAR Datasets` | Dataset | [Link]() |
| `03 - Python` | Complete analysis in Python | [Link]() |
| `04 - rfm_table`| RFM - Dataset | [Link]() |
| `05 - Presentation` | Presentation | [Link]() |
|`06 - Dashboard ` | Dashboard | [Link]() |


---

## 📌 Key Insights

- **High-Value Champions** represent ~20% of customers but drive the most revenue.
- **At-Risk** segment is the largest — strong potential for reactivation campaigns.
- Product preferences vary per segment, enabling personalized promotions.

---

## 📢 Strategic Recommendations

- Use loyalty programs and exclusives for High-Value customers.
- Upsell to Loyal customers using personalized offers.
- Reactivate At-Risk users with discounts or email nudges.
- Encourage One-Time buyers to repeat via bundles.

---

**Author:** Ahmed Ait si hamou  
**Role:** Data Analyst  
**Linkedin:** [Link](https://www.linkedin.com/in/ahmedaitsihamou/) 
**Project:** Portfolio / Customer Segmentation – RFM Analysis 

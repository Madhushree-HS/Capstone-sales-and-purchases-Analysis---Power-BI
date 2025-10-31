# 🧾Capstone sales and purchases Analysis-Power-BI

_A comprehensive analysis integrating sales transactions with supplier purchase data to optimize procurement, supplier relationships, and overall profitability._

---
## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#Method">Method</a>
- <a href="#key insights">Key-Insights</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>

---
<h2><a class="anchor" id="overview"></a>📘 Overview</h2>

This project combines sales data with supplier purchase information to provide a holistic view of business operations. It analyzes sales performance, customer behavior, supplier reliability, return patterns, and warranty effectiveness to support strategic decision-making across sales, procurement, and inventory management.

---
<h2><a class="anchor" id="problem-statement"></a>🎯 Problem-Statement</h2>

Businesses struggle to connect sales performance with supplier effectiveness. There's a need to identify which suppliers deliver quality products (low returns, good warranties), how supplier performance impacts customer satisfaction, and how to optimize procurement strategies to maximize profitability while minimizing risks.

---
<h2><a class="anchor" id="dataset"></a>📂 Dataset</h2>

**1. Sales Data:** Sales.htm (57 transactions, 28 attributes)

**2. Purchase Data:** Purchases.htm (54 purchase records, 9 attributes)

**3. Countries Data:** Countries.xlsx

**4. Total Integrated Dataset:** 57 records with combined sales and supplier attributes

---

<h2><a class="anchor" id="tools--technologies"></a>🛠 Tools & Technologies</h2>

**1. Excel Sheets:** Data integration using VLOOKUP/XLOOKUP, initial analysis

**2. Python (Pandas, NumPy, Matplotlib, Seaborn)**: Data merging, advanced analytics, visualization

**3. Power BI:** Interactive dashboards with drill-down capabilities

**4. SQL:** For database integration and querying (optional)

**5. Jupyter Notebook:** End-to-end reproducible analysis

---
<h2><a class="anchor" id="Method"></a>⚙ Method</h2>

**1. Data Integration:** Merge Sales and Purchases datasets using OrderID as key

**2. Data Cleaning:** Handle inconsistencies in dates, supplier names, return status

**3. Supplier Performance Metrics:** Return Rate by Supplier
                                  Warranty Effectiveness
                                  Feedback Score Analysis
                                  
**4. Cross-Dataset Analysis:** Supplier quality vs. Product ratings
                               Return patterns by Product Category
                               Warranty length impact on customer satisfaction
                            
**5. Time Series Analysis:** Purchase date vs. Sales date lead times

**6. Predictive Modeling:** Identify suppliers likely to have high return rates

---
<h2><a class="anchor" id="key-insights"></a>📊 Key-insights</h2>

**1. Supplier Performance:** Which suppliers have highest/lowest return rates

**2. Warranty Impact:** Correlation between warranty length and customer feedback

**3. Return Patterns:** Products/categories with highest return rates

**4. Supplier-Sales Rep Alignment:** Which sales reps work with most reliable suppliers

**5. Time Analysis:** Purchase-to-sale cycle times by supplier

**6. Risk Assessment:** High-return suppliers affecting profitability

**7. Customer Satisfaction:** Link between supplier quality and product ratings

---
<h2><a class="anchor" id="dashboard"></a>📈 Dashboard</h2>

**Integrated Dashboard with tabs for:** Sales Performance Overview
                                        Supplier Reliability Scorecard
                                        Return Analysis by Category/Supplier
                                        Warranty Effectiveness Metrics
                                        
**1. Supplier Rating System:** Composite score based on returns, warranty, feedback

**2. Alert System:** Flags for suppliers with return rates > 15%

**3. Interactive Filters:** By date range, product category, sales rep, supplier

---
<h2><a class="anchor" id="how-to-run-this-project"></a>▶ How to Run This Project</h2>

1. Download both Sales.htm and Purchases.htm and Coubtries.xlsx
2. Generate automated supplier performance report
3. Build interactive Power BI/Tableau dashboard

---
<h2><a class="anchor" id="final-recommendations"></a>✅ Final Recommendations</h2>

**Results:** Identified that suppliers with warranties > 24 months have 40% lower return rates. Found 3 suppliers with return rates > 25% affecting overall profitability.

**Conclusion:** Recommendations include renegotiating contracts with high-return suppliers, standardizing 24-month warranties across categories, and creating a supplier scorecard for procurement decisions. Integrated analysis reveals that supplier quality directly impacts customer satisfaction and repeat business.


---




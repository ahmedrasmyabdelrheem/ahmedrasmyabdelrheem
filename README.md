# 👋 Hi, I'm Ahmed Rasmy

<div align="center">

## Data & Business Intelligence Analyst

**Translating complex commercial data into strategic insights, executive dashboards, and measurable ROI.**

<br>

<a href="https://ahmedrasmyabdelrheem.github.io/">
  <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Website-111827?style=for-the-badge" alt="Portfolio">
</a>
<a href="https://www.linkedin.com/in/ahmedrasmyabdelrheem">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="mailto:ahmed.rasmy.abdelrheem@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

</div>

---

## 🚀 About Me

I'm a **Data & Business Intelligence Analyst** with an academic background in **Management Information Systems (MIS)** and intensive professional training from **DEPI and NTI**.

I bridge the gap between **business strategy and analytical data architecture**. Rather than writing isolated code, I partner with decision-makers to transform noisy operational, transactional, and customer clickstream data into clean relational data models (Star Schema), intuitive executive dashboards, and prioritized business recommendations.

My core expertise spans **omni-channel marketing intelligence, customer behavioral segmentation (RFM), commercial revenue analytics, and workforce attrition diagnostics**.

---

## 🛠️ Technical Skills

### 📊 Business Intelligence & Reporting
<p>
  <img src="https://img.shields.io/badge/Power_BI-Desktop_%26_Service-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-Data_Analysis_Expressions-205493?style=for-the-badge" alt="DAX">
  <img src="https://img.shields.io/badge/Power_Query-ETL_%26_Data_Prep-00758F?style=for-the-badge" alt="Power Query">
  <img src="https://img.shields.io/badge/Microsoft_Excel-Power_Pivot_%26_Modeling-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel">
</p>

### 🗄️ Database Architecture & SQL
<p>
  <img src="https://img.shields.io/badge/Microsoft_SQL_Server-SSMS-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/T--SQL-CTEs_%26_Window_Functions-00599C?style=for-the-badge" alt="T-SQL">
  <img src="https://img.shields.io/badge/Data_Architecture-Star_Schema_Design-blue?style=for-the-badge" alt="Star Schema">
  <img src="https://img.shields.io/badge/Data_Hygiene-Cleansing_%26_Deduplication-green?style=for-the-badge" alt="Data Hygiene">
</p>

---

## 💼 Featured Projects

### 1️⃣ 📊 Omni-Channel Marketing Analytics & Customer Journey Funnel
**Power BI · SQL Server · T-SQL · DAX · Star Schema · Clickstream Analytics**

> **🎯 The Business Challenge:**
> Commercial and marketing leadership allocated substantial spend across paid social, video, blogs, and search without unified visibility into channel attribution, customer conversion friction, or post-purchase product sentiment.

* **💡 The Analytical Solution:**
  * Architected an enterprise **Star Schema** in SQL Server connecting marketing touchpoints (`fact_engagement`), clickstream sessions (`fact_customer_journey`), and post-purchase feedback (`fact_customer_reviews`) with centralized dimension tables.
  * Cleansed clickstream event logs using T-SQL CTEs, `ROW_NUMBER()` deduplication, and window function duration imputation (`AVG() OVER()`).
  * Built an executive 3-page **Power BI** dashboard with fine-tuned visual interactions (`Edit Interactions`) to preserve benchmark context across categorical slicers.

* **📈 Key Business Discoveries & Value:**
  * **46M views** and **3M clicks** (**49M engagements**) at a **6.46% CTR**, identifying Video and Social Media as volume drivers and Blogs as the efficiency leader (~8.8% CTR).
  * Uncovered critical conversion friction: while overall conversion stands at **11.82%**, the checkout stage averages **222.5 seconds** (vs 89.1s on product pages), revealing high checkout form hesitation.
  * Correlated **1,804 customer reviews (3.98 / 5.0 rating)**, identifying that Footwear (3.3 / 5.0) and Southern Europe (3.1 / 5.0) suffer from sizing discrepancies and delivery lead-time delays.

🔗 **[View Project Repository →](https://github.com/ahmedrasmyabdelrheem/Omni-Channel-Marketing-Analytics-Customer-Journey-Funnel-)** · **[Open Live Power BI Dashboard →](https://app.powerbi.com/view?r=eyJrIjoiMDc2NDQ3M2YtOGI3NC00YTE3LTkzZDYtYjdmYjAxYzljMmFmIiwidCI6ImVhZjYyNGM4LWEwYzQtNDE5NS04N2QyLTQ0M2U1ZDc1MTZjZCIsImMiOjh9)**

---

### 2️⃣ 👥 Customer Behavioral Segmentation & RFM Value Optimization
**T-SQL · Power BI · Customer Lifetime Value (LTV) · Statistical RFM**

> **🎯 The Business Challenge:**
> Generic promotional outreach resulted in diminishing marketing ROI, unbudgeted discount erosion on loyal accounts, and undetected customer churn among formerly lucrative buyers.

* **💡 The Analytical Solution:**
  * Engineered a 5-stage **T-SQL pipeline** consolidating 12 monthly transactional partitions (2025-01 through 2025-12).
  * Calculated Recency, Frequency, and Monetary metrics, scoring **287 customer accounts** into statistical quintiles via `NTILE(5)` window functions.
  * Deployed an interactive **Power BI dashboard** enabling commercial teams to compare segments by revenue contribution, purchase recency, and churn risk.

* **📈 Key Business Discoveries & Value:**
  * Identified a high-margin core of **Champions (64 accounts, 22.3%)** and **Potential Loyalists (53 accounts, 18.5%)** driving the majority of commercial margins.
  * Isolated **42 high-value "At Risk" accounts (14.6%)** whose dormancy surged to **100–254 days**, triggering immediate high-priority win-back sequences.
  * Shifted **74 Hibernating accounts (25.8%)** to low-cost automated email workflows, protecting sales rep bandwidth and eliminating wasteful ad spend.

🔗 **[View Project Repository →](https://github.com/ahmedrasmyabdelrheem/rfm-customer-segmentation)** · **[Open Live Power BI Dashboard →](https://app.powerbi.com/view?r=eyJrIjoiOTNmNDQ0OTItM2YxMC00MTdhLWE0MGUtZmFmMGJjMDhlM2MzIiwidCI6ImVhZjYyNGM4LWEwYzQtNDE5NS04N2QyLTQ0M2U1ZDc1MTZjZCIsImMiOjh9)**

---

### 3️⃣ 📈 Commercial Revenue & Sales Performance Intelligence
**Microsoft Excel · Power Pivot · DAX · Power Query · Star Schema Architecture**

> **🎯 The Business Challenge:**
> Commercial leadership lacked unified visibility across products, customer demographics, and regional territories, blinding decision-makers to margin erosion from unmonitored discounting and operational delivery bottlenecks.

* **💡 The Analytical Solution:**
  * Cleansed and standardized multi-table transactional data (`customers`, `orders`, `products`) via **Power Query**.
  * Architected an enterprise **Star Schema** in **Power Pivot**, establishing 1-to-many relationships from dimension tables to the central fact table (`fOrders`).
  * Engineered business-critical DAX measures for Revenue, Average Customer Spend, Delivery Lead Times, and temporal order concentration.

* **📈 Key Business Discoveries & Value:**
  * Tracked **\$3,520,984** across 1,000 orders (**\$3,521 AOV**), identifying **"Colors" (\$1.02M)**, **Soft Toys (\$740K)**, and **Sweets (\$730K)** as primary revenue pillars.
  * Isolated extreme seasonality peaking in **March (~$720K)**, propelled by **Anniversary (\$680K)** and **Raksha Bandhan (\$650K)** consumer occasions.
  * Diagnosed dual daily ordering peaks (**6:00 AM** and **7:00–8:00 PM**) and delivery fulfillment lead times (**5.53 days**), prioritizing Tier-2 logistics corridors (Bareilly, Ghaziabad, Bhilai).

🔗 **[View Project Repository →](https://github.com/ahmedrasmyabdelrheem/sales-performance-dashboard)** · **[Explore Showcase & Download Model →](https://ahmedrasmyabdelrheem.github.io/#sales-project)**

---

### 4️⃣ 👥 People Analytics · Workforce Retention & Attrition Intelligence
**Microsoft Excel · Power Pivot · Workforce Analytics · Diagnostic Strategy**

> **🎯 The Business Challenge:**
> A growing organization faced unpredictable voluntary employee turnover, triggering unbudgeted recruitment costs and draining senior institutional knowledge without visibility into departmental root causes.

* **💡 The Analytical Solution:**
  * Diagnosed workforce telemetry across **1,600 employee records** (1,119 active workforce, 481 historical departures) using **Power Pivot**.
  * Modeled dynamic headcount, tenure groups, departure velocity, and voluntary exit triggers.

* **📈 Key Business Discoveries & Value:**
  * **Senior Talent Drain:** Employees with **+5 years of tenure** made up **47.3% of all 2026 departures (105 of 222 exits)**, representing significant operational vulnerability.
  * **Departmental Hotspots:** **Sales (62 exits)** and **Operations (47 exits)** accounted for nearly half of company turnover, driven by **Work-Life Balance (44)** and **Compensation (39)**.

🔗 **[Explore Dashboard on Portfolio →](https://ahmedrasmyabdelrheem.github.io/#projects)** · **[Download Excel Model (.xlsx) →](https://ahmedrasmyabdelrheem.github.io/assets/People_Analytics_Attrition_Intelligence.xlsx)**

---

## 🎯 Career Focus

I am actively seeking opportunities where I can apply **Business Intelligence and Data Analytics** to solve high-impact commercial, marketing, and operational business challenges.

**Target Roles**

`Data Analyst` · `Business Intelligence Analyst` · `BI Developer` · `Power BI Specialist`

---

## 🤝 Let's Connect

<div align="center">

<a href="https://ahmedrasmyabdelrheem.github.io/">
  <img src="https://img.shields.io/badge/🌐_Portfolio-Visit_Website-111827?style=for-the-badge" alt="Portfolio">
</a>
<a href="https://www.linkedin.com/in/ahmedrasmyabdelrheem">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="mailto:ahmed.rasmy.abdelrheem@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

<i>Transforming complexity into clarity through business storytelling and robust data architecture.</i>

</div>

# Customer Behavior Analysis — End‑to‑End Project

An end‑to‑end **customer shopping behavior analysis** project that uncovers **purchasing patterns**, **revenue drivers**, and **high‑value customer segments** to support **data‑driven business decisions**.

---

## 📌 Project Architecture

![Project Architecture](project_architecture.jpg)

---

## 📊 Dashboard Preview

![Dashboard Preview](dashboard_preview.png)

---

## 📊 Dashboard Demo
![](dashboard_demo.gif)

---

## 🎯 Project Objectives

- Identify **high‑value customer segments** and their characteristics  
- Understand **purchase behavior** across categories and demographics  
- Track **revenue drivers** and spending patterns  
- Deliver actionable insights through an interactive **Power BI dashboard** and a business report

---

## 🧰 Tech Stack

- **Python** (data ingestion & preprocessing)
- **PostgreSQl** (analysis queries)
- **Power BI** (interactive dashboard)
- Dataset: **CSV** (included)

---

## 📁 Data & Deliverables (Included)

- `customer_shopping_behavior.csv` — raw dataset  
- `Python Data Ingestion & Pre-Processing.ipynb` — preprocessing + preparation notebook  
- `customer_behavior_sql_queries.sql` — SQL analysis queries  
- `Customer Behavior Dashboard.pbix` — Power BI dashboard file  
- `Customer Shopping Behavior Business Report.pptx` — business presentation/report  
- `Project Requirements.pdf` — scope and requirements  

---

## 🚀 Step-by-Step: How to Run (End-to-End)

### Step 1 — Download the repository
Clone the repo or download it as ZIP.

### Step 2 — Review the problem statement
Open:
- `Project Requirements.pdf`  
This defines the **business questions**, expected KPIs, and dashboard/report requirements.

### Step 3 — Run data ingestion & preprocessing (Python)
Open and run:
- `Python Data Ingestion & Pre-Processing.ipynb`

**Goal:** transform the raw CSV into a **clean, analysis-ready** dataset (ready for SQL/Power BI).

> If you run this locally, ensure your environment has common data libraries (e.g., **pandas**, **numpy**).  
> Keep the dataset file path aligned with the notebook (or update it inside the notebook).

### Step 4 — Run SQL analysis (optional but recommended)
Use:
- `customer_behavior_sql_queries.sql`

**Goal:** validate KPIs, compute core metrics, and reproduce insights via **SQL**.

### Step 5 — Open the Power BI dashboard
Open:
- `Customer Behavior Dashboard.pbix` in **Power BI Desktop**

If Power BI prompts for data source paths:
1. Go to **Transform Data → Data source settings**
2. Update the path to your local CSV / processed output
3. Click **Refresh**

### Step 6 — Review the business report
Open:
- `Customer Shopping Behavior Business Report.pptx`  
This summarizes the findings and provides **business-ready recommendations**.

---

## ✅ Notes

- For the smoothest experience, keep the dataset file(s) in the same folder as the `.pbix` file or re-link them once and refresh.
- Use the SQL file to ensure metric consistency between **SQL outputs** and **Power BI visuals**.

---

## 🗂️ Repository Structure

```
.
├── README.md
├── Project Requirements.pdf
├── project_architecture.jpg
├── customer_shopping_behavior.csv
├── Python Data Ingestion & Pre-Processing.ipynb
├── customer_behavior_sql_queries.sql
├── Customer Behavior Dashboard.pbix
├── dashboard_preview.png
├── dashboard_demo.gif
└── Customer Shopping Behavior Business Report.pptx
```

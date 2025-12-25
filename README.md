# 📊 Data Analytics Project

## 🧭 Overview

This project demonstrates an end-to-end **Data Analyst–focused** analytics workflow, covering data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis, and business intelligence reporting. The goal is to transform raw data into meaningful insights and present them through an interactive Power BI dashboard, a written report, and a presentation created using Gamma.

The project closely mirrors real-world responsibilities of a **Data Analyst**, including working with structured data, writing SQL queries, validating data quality, and communicating insights to stakeholders.

---

## 📁 Dataset

* **Source:** Uploaded project dataset
* **File Name:** `customer_shopping_behavior.csv`
* **Format:** CSV
* **Size:** ~3900 rows × 18 columns
* **Description:** The dataset contains structured business data used to analyze trends, performance metrics, and category-level insights. It serves as the foundation for EDA, SQL analysis, and dashboard development.

---

## 🛠️ Tools & Technologies

* **Python:** Data loading, EDA, and data cleaning

  * Libraries: Pandas
* **PostgreSQL:** SQL queries and analytical transformations
* **Power BI:** Interactive dashboard and visualizations
* **Gamma:** Presentation (PPT) creation
* **Git & GitHub:** Version control and project documentation

---

## 🔄 Project Steps

1. **Data Loading**

   * Imported the dataset into Python using pandas.

2. **Exploratory Data Analysis (EDA)**

   * Analyzed data structure, distributions, and relationships.
   * Identified missing values, outliers, and inconsistencies.

3. **Data Cleaning & Preparation**

   * Handled missing values and duplicates.
   * Standardized column names and data types.
   * Prepared clean tables for analysis and reporting.

4. **SQL Analysis (PostgreSQL)**

   * Loaded cleaned data into PostgreSQL.
   * Wrote SQL queries for business related questions.
   * Created analysis-ready tables/views for Power BI.

5. **Dashboard Development (Power BI)**

   * Connected Power BI to PostgreSQL.
   * Built interactive visuals, KPIs, and filters.

6. **Reporting & Presentation**

   * Created a structured analytical report summarizing insights.
   * Developed a professional presentation using Gamma.

---

## 📈 Dashboard

The Power BI dashboard provides:

* Key performance indicators (KPIs)
* Trend analysis over time
* Category-wise and segment-wise breakdowns
* Interactive filters for deeper exploration

**Dashboard Highlights**

* Dynamic KPI cards for quick performance checks
* Drill-down enabled charts for detailed analysis
* Clean, business-friendly layout designed for decision-makers

> *<img width="1353" height="736" alt="customer_behavior_dashboard_SS" src="https://github.com/user-attachments/assets/8956c230-31e8-4ef5-b1b7-ab50ba7f9ab0" />
*

---

## ✅ Results & Insights

**Key KPIs**

* **Total Records Analyzed:** ~3900
* **Key Metric Growth:** ~18% increase compared to the previous period
* **Top Performing Category:** Clothing (contributing ~45% of total Revenue)
* **Lowest Performing Segment:** Outerwear (need to give discounts)
* **Data Quality Improvement:** Reduced missing values from ~7% to <1% after cleaning

**Insights**

* A small number of categories contribute a disproportionately large share of overall performance (Pareto pattern).
* Clear seasonal and trend-based patterns were identified, supporting better forecasting and planning.
* SQL-based aggregations significantly improved query performance and dashboard responsiveness.
* Power BI visuals enabled stakeholders to quickly identify underperforming segments and growth opportunities.

---

## ▶️ How to Run the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/chandrashekhar9262/customer_behavior_analysis
   cd customer_behavior_analysis
   ```

2. **Set Up Python Environment**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run Python Analysis**

   * Open and execute the Jupyter notebooks or Python scripts in the `notebooks/` or `src/` folder.

4. **Set Up PostgreSQL**

   * Create a PostgreSQL database.
   * Load the cleaned dataset into the database.
   * Run the SQL scripts provided in the `sql/` folder.

5. **Open Power BI Dashboard**

   * Open the `customer_behavior_dashboard.pbix` file in Power BI Desktop.
   * Update database credentials if required.

---

## 🧩 Project Architecture / Workflow

```
Raw Data (project_data.csv)
        ↓
Python (EDA & Data Cleaning)
        ↓
PostgreSQL Database
        ↓
SQL Queries & Views
        ↓
Power BI Dashboard
        ↓
Insights Report & Gamma Presentation
```

## 📦 Project Deliverables

* Python notebooks/scripts for EDA and data cleaning
* SQL queries for analysis
* Power BI dashboard
* Analytical report
* Presentation (Gamma PPT)

---

## 👤 Author

**Chandra Shekhar Kumar**
Data Analyst | Python | SQL | Power BI

---

## 📜 License

This project is for educational and portfolio purposes.

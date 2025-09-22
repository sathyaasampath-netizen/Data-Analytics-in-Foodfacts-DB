# Data-Analytics-in-Foodfacts-DB
FoodFactsDB is a SQL + Analytics project built on the Open Food Facts dataset.   The project explores relationships between food processing levels, nutrition, and health labeling, while practicing database design, querying, and statistical analysis.
# 🥗 FoodFactsDB – Open Food Facts Data Analytics

**FoodFactsDB** is a SQL + Analytics project built on the **Open Food Facts** dataset.  
The project explores relationships between food processing levels, nutrition, and health labeling, while practicing database design, querying, and statistical analysis.

---

## 📊 Features
- **Database Design & Setup**
  - Structured the Open Food Facts dataset into relational tables (products, nutrients, labels, countries).
  - Cleaned and normalized data for analysis.

- **SQL Queries**
  - Aggregated nutritional values by NOVA food processing groups.
  - Compared nutrient levels (e.g., fat, sugar) across organic vs. non-organic products.
  - Extracted subsets by countries and health labels (vegan, vegetarian, gluten-free).
  - Created analytical views for hypothesis testing and visualization.

- **Statistical Analysis**
  - Two-sample t-tests (e.g., fat content in NOVA Group 1 vs NOVA Group 4).
  - Cross-tabulations on label distributions.
  - Country-level comparisons of health-related food claims.

- **Case Study Research Questions**
  - **RQ1**: Do ultra-processed foods (NOVA 4) have higher fat content than minimally processed foods (NOVA 1)?  
  - **RQ2**: Is there a nutritional difference between organic vs. non-organic products?  
 
---

## 🔧 Tools & Technologies
- MySQL (Workbench, DDL/DML/DQL queries)
- Python (pandas, matplotlib for analysis & visualization)
- Microsoft Excel (t-tests & summary statistics)

---

## 📈 Key Insights
- Ultra-processed foods (NOVA 4) had significantly higher fat content than minimally processed foods (NOVA 1).  
- Labeling claims (organic, vegan) showed patterns in nutrient content, useful for consumer health awareness.  
- Cross-country comparisons revealed differences in food processing trends.  

---

## 🎯 Purpose
This project demonstrates the integration of **SQL database design, hypothesis-driven analytics, and statistical testing** to extract insights from real-world open data.

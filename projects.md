---
layout: page
title: My Projects
permalink: /projects/
---

## **Border Angels EOY Programs Dashboard**
**Technologies:** Python, Pandas, VS Code, Google Cloud Console, Google Sheets API, Data Visualization

**Description:** Built organization-wide reporting dashboard consolidating annual program data for humanitarian nonprofit serving migrants along the U.S.-Mexico border. Coordinated cross-departmental data collection and engineered Python ETL pipeline to automate monthly reporting, replacing manual processes with real-time KPI tracking.
Key Insights:

* Developed Python ETL pipeline using Pandas to extract, clean, and transform raw program data from multiple departments into standardized reporting format
* Automated data loading through Google Cloud Console integration, enabling monthly refresh cycles without manual intervention
8 Consolidated organizational KPIs revealing 27+ community events coordinated with 84+ unique volunteers throughout the year
* Tracked $84,405+ in program expenditures across all initiatives, providing leadership with financial visibility for budget planning
* Quantified community impact showing 1,362+ people served across Border Angels' shelter coordination and humanitarian programs

![Dashboard](/BA-Dashboard.png)

---

## **Google Analytics E-Commerce Dashboard**
**Technologies:** BigQuery SQL, Google Sheets Connected Sheets, Pivot Tables, Interactive Slicers, Data Visualization

**Description:** Built self-service analytics dashboard analyzing Google Analytics sample dataset (903,653 sessions, $1.54M revenue, Aug 2016 - Aug 2017). Engineered SQL views with advanced aggregations to enable multi-dimensional analysis of e-commerce performance across marketing channels, device categories, and geographic markets.
**Key Insights:**
* Designed BigQuery SQL views with UNNEST operations and aggregation functions to analyze 903K sessions across marketing channels, device types, and geographic markets
* Built interactive dashboard with 4 pivot tables and 6 slicers enabling real-time filtering and cross-dimensional performance analysis
* Identified mobile optimization opportunity: desktop generates 95.6% of revenue ($1.47M) while mobile drives 23% of traffic but only 3.2% revenue, representing significant conversion improvement potential
* Discovered referral channel drives 42% of revenue ($651K) with highest average order value across all traffic sources
* Analyzed geographic distribution showing United States accounts for 93.8% of revenue with opportunity for international expansion

[Live Demo](https://docs.google.com/spreadsheets/d/1a7nwZZNt5kNAkdBu2Ezm4Io1LKBuuTjDrpUF3jHWhvA/edit?usp=sharing) | [GitHub](https://github.com/RuizOsvaldo/google-analytics-dashboard)
---

## **Economic Indicators Analytics Dashboard**
**Technologies:** Python, pandas, SQL, fredapi, PostgreSQL, Google Sheets API

**Description:** Built an automated ETL pipeline and analytics dashboard to track macroeconomic indicators using Federal Reserve Economic Data (FRED) API. Features database storage, automated data refresh, and Google Sheets integration for stakeholder reporting.

**Key Insights:**
* Automated data extraction from Federal Reserve API for GDP, unemployment, inflation, and interest rate indicators
* Designed normalized PostgreSQL database schema for efficient storage and querying
* Wrote SQL queries for data aggregation, trend analysis, and historical comparisons
* Integrated Google Cloud APIs for automated reporting to Google Sheets
* Visualized economic trends with interactive time-series analysis

[Live Demo](https://docs.google.com/spreadsheets/d/1gdFmYrKiOba6NkbLmD7m4-hMJhArNtXMfkNYKQLs4_s/edit?usp=sharing) | [GitHub](https://github.com/RuizOsvaldo/economic-dashboard)

---

## **Sales Insights Dashboard**
**Technologies:** Python, pandas, plotly, Streamlit<br>
**Description:** Developed an interactive dashboard for visualizing sales data by region, category, and time trends. Enabled dynamic filtering and key performance metrics.

**Key Insights:**
- Visualized total sales and profits across regions
- Tracked monthly sales trends and seasonal patterns
- Highlighted performance by product category

[Live Demo](https://oruiz-sid.streamlit.app) | [GitHub](https://github.com/RuizOsvaldo/sales_insights_dashboard)

---

## **Customer Churn Analysis**
**Technologies:** Python, pandas, scikit-learn, seaborn, Streamlit<br>
**Description:** Built a machine learning dashboard to identify key factors influencing customer churn in a telecom dataset. Included performance metrics and feature importance visualization.

**Key Insights:**
- Identified top drivers of churn using Random Forest
- Displayed model performance with classification report and confusion matrix
- Visualized top 10 features contributing to churn

[Live Demo](https://oruiz-ccd.streamlit.app) | [GitHub](https://github.com/RuizOsvaldo/customer_churn_dashboard)

---

### **US Housing Market Analysis Dashboard**
**Technologies:** Tableau, US Census Data, Interactive Dashboards<br>
**Description:** Built a comprehensive housing market dashboard analyzing 53 years of US Census data (1963-2016) with interactive regional filtering, price trend analysis, and inventory insights. Features national price appreciation tracking, regional comparisons, and economic cycle visualization.

**Key Insights:**
- Housing prices increased 1,670% from 1963-2016, averaging 5.4% annual appreciation
- Regional housing inventory varies dramatically, creating supply-demand imbalances
- The 2008 financial crisis disrupted trends but full recovery occurred by 2012-2013
- National housing data provides comprehensive view while regional data focuses on inventory levels

[Live Demo](https://public.tableau.com/app/profile/osvaldo.ruiz3189/viz/U_S_HomeSales1963-2016_17543278409820/Dashboard?publish=yes)

---

## **Baseball Performance Analytics**
**Technologies:** Python, pandas, matplotlib, Streamlit, SQL<br>
**Description:** Built an interactive dashboard analyzing MLB player statistics using sabermetrics.

**Key Insights:**
- Analysizes player perfomances using sabermetrics
- Predicts outcome based on differnt factors, such as opposing pitcher, and stadium
- Uses a Machine Learning model to train future predictions and a database 

[Work in Progress]

---

## Skills Demonstrated
- **Data Cleaning & Processing:** pandas, numpy, handling missing data, categorical encoding
- **Statistical Analysis & Machine Learning:** Random Forests, model evaluation (classification reports, confusion matrices), train/test split
- **Visualization:** matplotlib, seaborn, plotly (bar charts, line charts, feature importance), Tableau
- **Web Applications:** Streamlit dashboards with sidebar filtering, expandable sections, and interactive KPIs
- **Databases:** SQL, data extraction, datetime transformations
- **Business Intelligence:** KPI development, customer segmentation, churn risk analysis, revenue/profit breakdowns, and sales trend forecasting

---

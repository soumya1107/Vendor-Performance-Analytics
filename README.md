📊 Vendor Data Analytics & Performance Intelligence
🔍 Project Overview
<img width="1411" height="891" alt="image" src="https://github.com/user-attachments/assets/abb97a6a-2cf9-4da1-918d-1d7eaab859d5" />

This project is an end-to-end Vendor Data Analytics solution designed to analyze large-scale sales and inventory data and derive actionable insights on vendor performance.

The objective was not just analysis, but to simulate a real-world analytics pipeline — from raw data ingestion to statistical validation and executive-ready dashboards.

The project handles 20+ million records, making it a strong demonstration of scalability, analytical depth, and business-oriented thinking.

🧱 Data Architecture & Storage

Built a SQLite database to efficiently store and query large datasets

Ingested multiple structured datasets into relational tables:

sales

begin_inventory

end_inventory

purchase_prices

purchases

vendor_invoice

Designed the schema to support cross-table analysis on vendors, time periods, inventory movement, and pricing

This setup mirrors a real analytics backend where data is normalized, queryable, and reusable.

🧪 Exploratory Data Analysis (EDA)

Performed deep EDA to understand patterns, anomalies, and performance drivers using:

pandas → data manipulation & feature engineering

matplotlib & seaborn → visual exploration and trend analysis

Key EDA themes included:

Vendor-wise sales distribution

Inventory turnover patterns

Price vs volume relationships

Identification of high-performing vs underperforming vendors

Seasonality and demand variability

EDA outputs were used to form hypotheses, not just generate plots.

📐 Statistical Analysis & Hypothesis Testing

To move beyond descriptive analytics, I applied statistical inference techniques:

Segmented vendors into top-performing and low-performing cohorts

Conducted hypothesis testing to compare vendor performance metrics

Calculated 95% Confidence Intervals (CI) to:

Validate whether observed performance differences were statistically significant

Reduce decision-making based on noise or outliers

This step ensures that insights are data-backed and statistically reliable, not just visually appealing.

📊 Power BI Dashboard & Visualization Layer

Built an interactive Power BI dashboard to translate analysis into business insights.

Dashboard Features:

Vendor performance KPIs

Sales, inventory, and pricing trends

Top vs low-performing vendor comparisons

Interactive slicers (vendor, time period, category, etc.)

Custom DAX measures for dynamic metrics

The dashboard is designed for:

Business stakeholders

Operations teams

Vendor management & procurement decisions

This makes the project decision-ready, not just analysis-ready.

🛠️ Tools & Technologies Used

Python: pandas, matplotlib, seaborn

Database: SQLite

Statistics: Hypothesis testing, confidence intervals

Visualization: Power BI (DAX, slicers, measures)

Data Scale: 20+ million records

🎯 Key Takeaways

Demonstrates ability to work with large datasets

Combines EDA + statistics + visualization into one coherent workflow

Bridges the gap between technical analysis and business insights

Reflects real-world analytics problems in vendor and supply-chain domains

🚀 Why This Project Matters

This project showcases how raw transactional data can be transformed into:

Clear performance narratives

Statistically validated insights

Interactive dashboards for decision-making

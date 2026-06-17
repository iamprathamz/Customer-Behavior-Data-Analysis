# Customer Shopping Behavior Analysis

## 📊 Project Overview
A leading retail company aims to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty[cite: 6]. This project analyzes consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies[cite: 6]. 

## 📁 Repository Contents
This project relies on and references the following files:

* **`Business Problem  Document.pdf`**: Outlines the core business objectives, problem statement, and required project deliverables[cite: 6].
* **`customer_shopping_behavior (1).csv`**: The raw dataset containing 3,900 purchases and 18 behavioral/demographic columns[cite: 5, 6].
* **`Customer_Shopping_Behavior_Analysis.ipynb`**: The Python notebook handling data preparation, cleaning, missing value imputation, and database integration[cite: 5, 6].
* **`customer_behavior_sql_queries.sql`**: SQL scripts containing structured queries used to extract business insights and answer key overarching questions[cite: 5, 6].
* **`customer_behavior_dashboard.pbix`**: An interactive Power BI dashboard highlighting key patterns, trends, and visualizations[cite: 5, 6].
* **`Customer-Shopping-Behavior-Analysis (2).pptx`**: A presentation visually communicating insights and actionable recommendations to stakeholders[cite: 6].
* **`Customer Shopping Behavior Analysis.pdf`**: The final comprehensive project report summarizing key findings and business recommendations[cite: 6].

## 🛠️ Tech Stack
* **Python** (Pandas, SQLAlchemy): Used for data cleaning, transformation, feature engineering, and database loading[cite: 3, 5, 6].
* **SQL** (PostgreSQL/MySQL/SQL Server): Used for structured data analysis and business logic extraction[cite: 3, 5, 6].
* **Power BI**: Used for interactive data visualization and dashboarding[cite: 5, 6].

## 🚀 Methodology
1. **Data Preparation**: Cleaned the raw data using Python, imputed missing values in the `Review Rating` column, standardized column names to snake_case, and engineered new tracking features like `age_group` and `purchase_frequency_days`[cite: 3, 5].
2. **Database Integration**: Connected the Python script to a PostgreSQL database to load the cleaned data for querying[cite: 3, 5]. Scripts for MySQL and MS SQL Server were also documented[cite: 3].
3. **Data Analysis**: Executed SQL queries to segment customers, analyze revenue by demographics, evaluate shipping preferences, and identify top-performing products[cite: 5, 6].
4. **Visualization**: Developed a Power BI dashboard to present insights visually to stakeholders to drive data-driven decision-making[cite: 5, 6].

## 💡 Key Insights
* **Demographics**: Male customers generated $157,890 in total revenue compared to $75,191 from female customers[cite: 5].
* **Customer Segmentation**: The customer base consists of 50% "New" buyers, 35% "Returning" shoppers, and 15% high-value "Loyal" customers[cite: 4, 5].
* **Shipping Preferences**: Customers opting for Express Shipping spend an average of $60.48 per transaction, which is roughly 12% more than those using Standard Shipping ($58.46)[cite: 4, 5].
* **Subscription Value**: Subscribers account for a significant 45% revenue share and represent a large portion of repeat buyers, showcasing a high loyalty rate[cite: 4, 5].
* **Product Satisfaction**: Gloves and Blouses received the highest average customer satisfaction ratings across the catalog[cite: 4, 5].

## 🎯 Business Recommendations
* **Boost Subscriptions**: Promote exclusive benefits to increase subscription rates and drive predictable revenue[cite: 4, 5].
* **Enhance Loyalty Programs**: Reward repeat buyers to successfully transition them from the "New" and "Returning" segments into the top-tier "Loyal" segment[cite: 4, 5].
* **Targeted Marketing**: Direct marketing efforts and specialized campaigns toward high-revenue age groups and customers who frequently utilize express shipping[cite: 4, 5].
* **Product Positioning**: Highlight top-rated products heavily in promotional materials to capitalize on existing consumer satisfaction[cite: 4, 5].

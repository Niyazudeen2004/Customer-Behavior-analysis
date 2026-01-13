# Customer-Behavior-analysis
🔍 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into purchasing patterns, customer segments, product performance, and subscription behavior. The analysis combines Python, SQL, and Power BI to deliver business-ready insights and visual storytelling.

The project demonstrates an end-to-end data analytics workflow from raw data to business recommendations.

📁 Dataset

Source: Customer shopping transactional dataset

Rows: ~3,900

Columns: 18

Key Features:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season, Size, Color)

Behavior metrics (Discount, Promo Code, Review Rating, Purchase Frequency, Shipping Type)

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL (PostgreSQL / MySQL / SQL Server)

Power BI Desktop

Jupyter Notebook

Gamma (for PPT creation)

GitHub (version control & documentation)

⚙️ Project Workflow / Steps
1. Data Loading

Loaded dataset into Python using Pandas.

Verified structure using info() and describe().

2. Exploratory Data Analysis (EDA)

Distribution of purchase amounts.

Category and season analysis.

Customer demographic patterns.

Review rating trends.

3. Data Cleaning

Handled missing values in review ratings.

Standardized column names.

Created new features:

age_group

purchase_frequency_days

Removed redundant columns after validation.

4. Database Integration

Loaded cleaned dataset into SQL database.

Performed structured SQL analysis.

5. SQL Analysis

Answered business questions such as:

Revenue by gender

High-spending discount users

Top rated products

Shipping type comparison

Subscribers vs non-subscribers

Discount-dependent products

Customer segmentation

Revenue by age group

6. Power BI Dashboard

Built an interactive dashboard showing:

Total customers

Average purchase amount

Average rating

Revenue by category

Sales by age group

Subscription distribution

7. Reporting & Presentation

Created analytical report document.

Designed business PPT using Gamma.

📈 Dashboard

The Power BI dashboard provides an interactive and business-friendly view of customer behavior, enabling filtering by:

Category

Gender

Subscription status

Shipping type

Age group

It helps stakeholders quickly identify revenue drivers and customer trends.

📊 Key Results

Non-subscribers generate higher total revenue due to volume.

Express shipping users spend more on average.

Certain products rely heavily on discounts.

Loyal customers dominate the customer base.

Young adults contribute the highest revenue.

Review ratings strongly influence product performance.

💡 Business Recommendations

Promote subscription benefits.

Improve loyalty programs.

Optimize discount strategies.

Focus marketing on high-revenue age groups.

Highlight top-rated products in campaigns.

▶️ How to Run This Project
Python
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2


Open Jupyter Notebook and run the analysis notebook.

SQL

Import cleaned dataset into PostgreSQL / MySQL / SQL Server.

Execute SQL queries from the provided SQL file.

Power BI

Connect Power BI to the SQL database.

Load tables and build visuals using provided measures.

📂 Project Structure
Customer-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard.pbix
├── report.pdf
├── presentation.pptx
└── README.md

🎯 Skills Demonstrated

Data Cleaning & Feature Engineering

SQL Business Analysis

Dashboard Design

Storytelling with Data

Business Insight Generation

End-to-End Analytics Workflow

👤 Author

Niyazudeen K

B.Tech Robotics & Automation

Aspiring Data Analyst

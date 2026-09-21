📊 Supermarket Business Intelligence & Analytics Dashboard

An end-to-end Data Analytics project powered by Power BI to evaluate financial metrics, sales trends, customer behavior, and category performance for a retail supermarket network.

🖼️ Dashboards Preview

1. Sales & Financial Performance Overview_(num1.png)

2. Customer & Product Insights Overview

📑 Executive Summary

This repository contains an interactive two-page Power BI dashboard designed to give stakeholders full visibility into retail operations. It combines high-level financial KPIs with granular transactional and demographic insights to drive data-informed decision-making.

💾 Dataset Overview (supermarket.csv)

The underlying dataset contains transactional records from 3 supermarket branches (Naypyitaw, Yangon, Mandalay) across various product categories.

Column Field

Description

Type

Invoice ID

Unique transaction identifier

Text

Branch / City

Store branch (A, B, C) and city location

Categorical

Customer Type

Member vs. Normal customer

Categorical

Gender

Customer gender (Female / Male)

Categorical

Product Line

Item category (e.g., Food & Beverages, Electronic Accessories)

Categorical

Unit Price / Quantity

Price per unit ($) and quantity purchased

Numeric

Tax 5% / Total

Calculated tax and total transaction amount ($)

Numeric

Date / Time

Timestamp of transaction

Date/Time

Payment

Payment method used (Cash, Credit Card, E-wallet)

Categorical

Rating

Customer satisfaction score (1 to 10 scale)

Numeric

📈 Dashboard Breakdown & Visual Analysis

🟢 1. Sales & Financial Performance (num1.png)

Focuses on revenue generation, tax accounting, unit volume, and revenue drivers across locations and product lines.

🎯 Key Performance Indicators (KPIs)

Total Sales ($322.97K): Gross revenue generated across all transactions.

Net Sales Before Tax ($307.59K): Core sales figure excluding tax contributions.

Total Tax ($15.38K): Total 5% VAT collected.

Total Quantity (6K): Total units sold across all lines.

Number of Invoices (1K): Total order volume processed.

Average Bill Value ($322.97): Average dollar spend per transaction.

Average Unit Price ($55.67): Average price point across product categories.

📊 Chart & Visual Analysis

Total Sales by Month (Area Line Chart):

Trend Analysis: Shows high sales volume in January (~$116K), followed by a dip in February (~$97K), and a strong recovery in March (~$109K).

Sales by City (Bar Chart):

Geographic Performance: Revenue distribution is highly balanced across cities: Naypyitaw ($111K), Yangon ($106K), and Mandalay ($106K).

Sales by Product Line (Horizontal Bar Chart):

Top Earners: Food and Beverages leads gross sales ($56K), followed closely by Sports and Travel ($55K) and Electronic Accessories ($54K).

Sales by Payment (Donut Chart):

Payment Channels: E-wallet leads with 34.74% ($112.21K), Cash accounts for 31.2% ($100.77K), and Credit Card takes 34.06% ($109.93K).

Branch & Product Line Matrix (Detailed Table):

Displays granular performance metrics comparing branches against product categories, total sales, items sold, and average ratings.

🔵 2. Customer & Product Insights (num.png)

Focuses on shopper demographics, peak traffic hours, customer satisfaction, and product rating trends.

🎯 Key Performance Indicators (KPIs)

Average Rating (6.97 / 10): Overall customer satisfaction baseline.

Member Sales % (50.85%) vs. Normal Sales % (49.15%): Customer retention and loyalty ratio.

Female Sales % (51.98%) vs. Male Sales % (48.02%): Gender demographic breakdown.

Avg Quantity per Invoice (5.51): Basket size per checkout.

Top Branch by Rating (Branch C): Store branch leading in overall satisfaction.

📊 Chart & Visual Analysis

Sales by Hour of the Day (Line Chart):

Traffic Dynamics: Identifies peak shopping hours at 14:00 (2 PM) (~$34.7K) and 19:00 (7 PM) (~$39.7K), highlighting optimal times for store staffing and cashier allocations.

Product Line by Average Rating (Horizontal Bar Chart):

Customer Satisfaction: Food and Beverages scores highest in customer ratings (7.1), while Home and Lifestyle sits at the lower end (6.8).

Quantity & Sales Relationship (Scatter Plot):

Volume vs. Value: Evaluates category placement by total unit volume vs. revenue generated to spot high-margin vs. high-volume inventory.

Customer Type Breakdown (Color-Coded Heatmap Table):

Compares revenue and items sold based on membership tier (Member vs. Normal) across product lines.

Branch by Average Rating (Column Chart):

Branch Satisfaction: Branch C (7.1 rating) > Branch A (7.0 rating) > Branch B (6.8 rating).

💡 Key Business Takeaways & Recommendations

Staffing Optimization: Schedule additional cashier and floor staff around 2 PM and 7 PM to handle daily peak volume surges efficiently.

Product Focus: Food and Beverages is the core revenue driver and holds the highest customer rating (7.1). Expand product offerings in this category.

Loyalty Program Conversion: Normal customers make up 49.15% of sales; offering sign-up incentives at checkout could significantly boost membership conversion.

Payment Gateway Reliability: E-wallets and Cards represent >68% of total transactions. Ensuring zero downtime in digital point-of-sale systems is vital.

📂 Repository Structure

.
├── Dashboard Supermarket.pbix   # Primary Power BI Dashboard File
├── supermarket.csv               # Raw Dataset
├── num1.png                     # Page 1 Screenshot (Sales & Financials)
├── num.png                      # Page 2 Screenshot (Customer Insights)
└── README.md                    # Project Documentation


🛠️ Requirements & How to Run

Clone this repository:

git clone https://github.com/ahmedelsayeddev1/YOUR-REPO-NAME.git


Download and install Power BI Desktop.

Open Dashboard Supermarket.pbix to explore the interactive visual features, filters, and slicers.

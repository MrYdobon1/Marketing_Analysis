# Marketing_Analysis
Marketing Analysis using Power BI

This dashboard provides an analysis of a supermarket's marketing campaigns. It consists of three pages: Market Overview, Customer Profiling, and Marketing & Campaign Effectiveness.

The dataset was obtained from Kaggle at https://www.kaggle.com/datasets/jackdaoud/marketing-data. The dataset is in CSV format, and all data cleaning was performed in Power BI.

## Data cleaning process
I split the dataset, which originally consisted of a single table, into four tables to make it easier to build the dashboard. I also made several changes, such as unpivoting the columns ‘maritalStatus’, ‘educationStatus’, ‘campaignName’, ‘productCategory’, and ‘channel’.

<img width="776" height="527" alt="image" src="https://github.com/user-attachments/assets/7882ac9b-609f-4c1d-a62d-8bea19e6be08" />

---

## 1. Market Overview
<img width="4150" height="2400" alt="campaignfix_page-0001" src="https://github.com/user-attachments/assets/fdfce4a8-c3d3-4226-bb14-7d8500b919b0" />

The Market Overview page provides an overview of sales at the supermarket. There are four Key Performance Indicator (KPI) cards:

1. **Average Spending** = Calculated based on the average purchase amount per customer.
2. **Total Customers** = The total number of customers.
3. **Total Revenue** = Calculated based on the total sales of all products in the supermarket.
4. **Gold Product Sales** = Calculated by dividing total revenue by the total sales of products in the ‘gold’ category.

This page also features three charts:

1. **Pie Chart** = Shows product sales distribution, including the total sales and the share of sales for each product.
2. **Bar Chart** = Shows purchase channels, including the channels through which each sale was made, such as in-store purchases, online purchases, and catalog purchases.
3. **Treemap** = Provides an overview of customer spending based on the selected slicer list (Age Group, Education Level, Marital Status).

This page features three dropdown slicers for filtering the chart based on Age Group, Education Status, and Marital Status. Specifically, for the Age Group, the data—which originally included ages—has been grouped as follows:

1. Young Adult = 18 - 35 years
2. Adult = 36 - 55 years
3. Middle Age = 56 - 65 years
4. Senior = 66+ years

---

## 2. Customer Profiling
<img width="4150" height="2400" alt="campaignfix_page-0002" src="https://github.com/user-attachments/assets/5e988c68-4f87-49ed-bf67-7a5417c87dc6" />

The customer profiling page contains demographic information and a breakdown of each customer category. There are two Key Performance Indicator (KPI) cards:

1. **Average Spending** = Calculated based on the average purchase amount per customer.
2. **Average Income** = Calculated based on the average income per customer.

This page also features three charts:

1. **Scatter Chart** = Shows a comparison of total spending and income based on the selected slicer list (Age Group, Education Level, Marital Status).
2. **Treemap** = Shows the total number of customers based on the selected slicer list (Age Group, Education Level, Marital Status).
3. **Column Chart** = Shows the average customer spending based on the selected slicer list (Age Group, Education Level, Marital Status).

This page features three dropdown slicers for filtering the chart based on Age Group, Education Status, and Marital Status.

---

## 3. Marketing & Campaign Effectiveness
<img width="4150" height="2400" alt="campaignfix_page-0003" src="https://github.com/user-attachments/assets/359354fd-00ec-4363-b9c2-d6d3b5536534" />
The Marketing & Campaign Effectiveness page contains statistics for each campaign conducted. There are five Key Performance Indicator (KPI) cards:

1. **Total Complaints** = Displays the total number of customer complaints.
2. **Conversion Rate** = Calculates the campaign’s success rate by dividing the number of people who “agreed/purchased” by the total number of customers.
3. **Top Responders** = Lists customers who participated in 3 or more campaigns.
4. **Acceptance Rate** = Calculates the percentage of customers who participated in at least 1 campaign out of the total number of customers.
5. **Deals Ratio** = Calculates the percentage of transactions made with discounts or special offers out of the total sales.

This page also features three charts:

1. **Gauge Chart** = Calculates the percentage of transactions made with discounts or special offers out of total sales.
2. **Bar Chart** = Shows the performance of 5 campaigns based on the number of responses received.
3. **Line and Column Chart** = Shows a comparison and correlation between the number of website purchases and the average number of website visits based on the selected slicer list (Age Group, Education Level, Marital Status).

This page features three dropdown slicers for filtering the chart based on Age Group, Education Status, and Marital Status.

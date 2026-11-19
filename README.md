<<<<<<< HEAD
# Optimizing E-Commerce Marketing Funnel Performance

An end-to-end data analytics project that evaluates e-commerce marketing performance, identifies customer conversion bottlenecks, and provides data-driven business recommendations using Python, SQL, and Power BI.

---

## Summary

This project analyzes an e-commerce marketing funnel dataset containing over 120,000 customer interaction records. The objective is to evaluate overall business performance, identify key conversion bottlenecks, compare marketing channel effectiveness, and generate actionable recommendations for improving marketing ROI and customer conversion.

The project follows a complete analytics workflow including SQL data extraction, Python-based data cleaning and exploratory analysis, statistical testing, and interactive dashboard development in Power BI.

---

## Skills Applied

- Data Cleaning & Data Validation
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Querying & Data Aggregation
- Statistical Analysis & Hypothesis Testing
- Business Intelligence Dashboard Design
- Data Storytelling & Business Recommendation

---

## Features

- Cleaned and transformed raw marketing funnel data using Python (Pandas)
- Performed SQL aggregation and business metric analysis using SQLite
- Conducted exploratory data analysis and statistical validation
- Built an interactive three-page Power BI dashboard
- Identified customer conversion bottlenecks and high-performing marketing channels
- Generated data-driven business recommendations

---

## Tech Stack

**Programming Language**
- Python

**Database**
- SQLite

**Visualization**
- Power BI

**Libraries**
- Pandas
- NumPy
- Matplotlib
- SciPy
- Statsmodels

**Tools**
- Jupyter Notebook

---

## Demo

### Executive Dashboard

![Executive Dashboard](figures/dashboard_page1.png)

### Marketing Funnel Analysis

![Marketing Funnel Analysis](figures/dashboard_page2.png)

### Customer & Marketing Insights

![Customer & Marketing Insights](figures/dashboard_page3.png)

---

## Background and Problem

Many e-commerce businesses invest heavily in marketing but lack visibility into where customers abandon the purchasing journey and which marketing channels deliver the greatest business value.

This project aims to answer the following business questions:

- How is the business performing overall?
- Where do customers drop off in the marketing funnel?
- Which marketing channels perform best?
- Which customer segments contribute the most revenue?
- What business actions should be prioritized?

---

## Project Workflow

Raw Data

↓

SQL (SQLite)

↓

Python Data Cleaning

↓

EDA & Statistical Analysis

↓

Power BI Dashboard

↓

Business Insights & Recommendations

---


## How to Run

```bash
git clone https://github.com/jiajialiang32-ui/E-Commerce-Marketing-Funnel-Analytics.git

cd E-Commerce-Marketing-Funnel-Analytics

pip install -r requirements.txt

jupyter notebook notebooks/marketing_funnel_analysis.ipynb
```

=======
# Ecomm-Funnel-Analysis

An end-to-end analytical project focused on a simulated e-commerce dataset, designed to study customer behavior throughout the purchase journey. The project examines session-level interactions, conversion trends across various user segments, and evaluates the effectiveness of marketing channels using business performance metrics.

## Project Objective

The objective of this project is to understand customer behavior across different stages of the e-commerce funnel, beginning with website visits and ending with successful purchases. It also aims to assess the impact of marketing channels using important business metrics such as Conversion Rate, Customer Acquisition Cost (CAC), and Return on Investment (ROI), helping teams make data-driven decisions.

## Key KPIs Monitored

* Funnel conversion analysis across stages (Visit → Product View → Cart → Checkout → Purchase)
* Conversion performance based on device type and user location
* Marketing channel effectiveness (Email, Instagram, Google Ads)
* ROI and Customer Acquisition Cost for each campaign channel
* Session-level metrics including event flow and engagement duration

## Visualizations Included

The analysis contains five important visual reports:

* Funnel stage drop-off analysis
* Marketing channel conversion comparison
* Customer Acquisition Cost (CAC) by channel
* User distribution across device categories
* Return on Investment (ROI) comparison chart

All generated visual outputs are stored inside the `visuals/` directory for easy reference.

## Tech Stack

* Python 3.x
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Jupyter Notebook
* Markdown

## Major Findings

* Email marketing produced the strongest results with the highest ROI (32,000%) and the lowest customer acquisition cost.
* The largest number of users exited the process between the cart and checkout stages, indicating possible issues in the purchase flow.
* Mobile users showed slightly lower conversion rates than desktop users, highlighting an opportunity to improve mobile usability.
* Bangalore and Delhi demonstrated stronger conversion performance compared to other locations.
* Instagram generated a high volume of traffic but was less efficient in terms of return on investment.

## Business Recommendations

* Increase focus and budget allocation toward Email campaigns due to their high efficiency.
* Enhance the mobile user experience, especially during payment and checkout steps.
* Improve the transition from cart to checkout by simplifying the process and reducing unnecessary steps.
* Introduce location-specific campaigns and promotions for high-performing regions.
* Optimize Instagram advertising strategies to improve campaign effectiveness and profitability.

## Project Deliverables

* Cleaned and transformed e-commerce dataset
* KPI calculations and analytical insights
* Visual dashboards and charts
* Complete GitHub project documentation
>>>>>>> e1b9708bee9eab25a692b1d2b0fc22d96c4cead2

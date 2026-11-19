# E-Commerce Marketing Funnel Analysis

An end-to-end data analytics project focused on understanding customer behaviour, tracking e-commerce conversion rates, and evaluating marketing campaign performance using Python, MySQL, and Power BI.

## Project Overview

This project explores an e-commerce marketing dataset containing more than 120,000 customer interaction records. The main goal was to understand how users move through different stages of the purchasing journey, identify where potential customers drop off, and determine which marketing channels generate the best results.

I worked through the complete data analytics process, starting with data cleaning and preparation, followed by MySQL-based analysis, exploratory data analysis, statistical testing, and interactive dashboard development in Power BI.

The analysis helped uncover important patterns in customer behaviour and provided practical recommendations to improve conversion rates and marketing ROI.

## Project Objectives

- Understand customer behaviour across different stages of the purchasing journey.
- Identify where customers are dropping off in the conversion funnel.
- Compare the performance of different marketing channels.
- Evaluate campaign effectiveness using ROI and Customer Acquisition Cost (CAC).
- Analyse conversion trends across devices and geographical locations.
- Provide actionable recommendations based on the findings.

## Key Metrics Analysed

- **Conversion Rate:** Percentage of users completing a purchase.
- **Customer Acquisition Cost (CAC):** Cost of acquiring a customer through different marketing channels.
- **Return on Investment (ROI):** Revenue generated compared to marketing expenditure.
- **Funnel Drop-off Rate:** Percentage of users leaving at each stage of the purchasing journey.
- **Channel Performance:** Comparison of conversion rates and profitability across marketing channels.
- **Customer Engagement:** Session activity and time spent interacting with the platform.

## Tools and Technologies

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Statistical Analysis | SciPy, Statsmodels |
| Database | MySQL |
| Business Intelligence | Power BI |
| Development Environment | Jupyter Notebook |

## Work Performed

1. **Data Cleaning and Preparation:** Used Python and Pandas to handle missing values, check data consistency, remove duplicates where necessary, and prepare the dataset for analysis.

2. **SQL Analysis:** Used MySQL to write queries, perform data aggregation, analyse customer behaviour, and calculate important business metrics.

3. **Exploratory Data Analysis (EDA):** Analysed customer interactions, purchasing patterns, conversion trends, and marketing channel performance to identify meaningful insights.

4. **Statistical Analysis:** Applied statistical techniques and hypothesis testing to validate observations and understand differences in performance.

5. **Dashboard Development:** Created an interactive, three-page Power BI dashboard to present business performance, funnel conversion trends, and marketing insights.

6. **Business Recommendations:** Converted analytical findings into practical suggestions for improving customer experience and marketing efficiency.

## Key Findings

- Email marketing delivered the highest ROI (32,000%) and had the lowest customer acquisition cost among the analysed channels.
- The biggest customer drop-off occurred between the cart and checkout stages, suggesting potential problems in the purchasing process.
- Mobile users had slightly lower conversion rates than desktop users, indicating room for improvement in the mobile shopping experience.
- Bangalore and Delhi showed comparatively stronger conversion performance than other locations.
- Instagram generated considerable website traffic but delivered lower ROI compared to email marketing.

## Business Recommendations

Based on the analysis, I identified the following opportunities:

- Allocate more resources to email marketing campaigns because of their strong ROI and lower acquisition costs.
- Simplify the checkout process to reduce customer drop-offs.
- Improve the mobile shopping experience, particularly during checkout and payment.
- Run targeted campaigns in locations with stronger conversion performance.
- Review Instagram advertising strategies to improve campaign profitability rather than focusing only on traffic generation.

## Power BI Dashboard

The dashboard is divided into three sections to make the findings easier to explore.

### 1. Executive Dashboard

![Executive Dashboard](figures/dashboard_page1.png)

Provides an overview of overall business performance and key KPIs.

### 2. Marketing Funnel Analysis

![Marketing Funnel Analysis](figures/dashboard_page2.png)

Highlights customer movement through the funnel and identifies the stages with the highest drop-off rates.

### 3. Customer and Marketing Insights

![Customer and Marketing Insights](figures/dashboard_page3.png)

Explores customer segments, marketing channel performance, and geographical trends.

## Project Workflow

Raw Dataset → Data Cleaning → MySQL Analysis → Exploratory Data Analysis → Statistical Testing → Power BI Dashboard → Business Recommendations

## Project Structure

```text
E-Commerce-Marketing-Funnel-Analysis/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── marketing_funnel_analysis.ipynb
│
├── figures/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│   └── dashboard_page3.png
│
├── visuals/
│
├── requirements.txt
└── README.md
```

## How to Run the Project

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project directory**

```bash
cd E-Commerce-Marketing-Funnel-Analysis
```

**3. Install the required Python libraries**

```bash
pip install -r requirements.txt
```

**4. Set up MySQL**

- Install and start MySQL Server.
- Create a database for the project.
- Import the dataset into the database.
- Update the database connection credentials in the notebook or configuration file.

**5. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `marketing_funnel_analysis.ipynb` and run the cells to explore the analysis.

## Project Deliverables

- Cleaned and processed e-commerce dataset.
- Python notebook containing data cleaning, EDA, and statistical analysis.
- MySQL queries for business metric calculations.
- Interactive three-page Power BI dashboard.
- Visual reports highlighting customer and marketing performance.
- Business insights and actionable recommendations.

## What I Learned

Through this project, I gained practical experience in working with customer interaction data, writing MySQL queries, performing exploratory and statistical analysis, building interactive dashboards, and translating analytical results into meaningful business recommendations.

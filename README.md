E-commerce Data Analysis Project
Overview
This project analyzes an e-commerce dataset to understand customer behavior, product performance, and business patterns.
The analysis covers data cleaning, exploratory data analysis (EDA), hypothesis testing, and visualization to extract actionable business insights.

The goal is to:

Assess data quality and clean the dataset

Explore trends in sales, returns, reviews, discounts, and delivery performance

Test business hypotheses using statistical methods

Provide visual evidence and recommendations for decision-making

Methodology
Data Loading

Dataset loaded from CSV (Google Sheets export or local file)

Columns include: order details, customer demographics, product attributes, delivery info, and review ratings

Data Cleaning

Converted date columns to datetime format

Removed duplicates

Handled missing values (imputation or removal based on context)

Created derived features such as final_price, discount_percent, delivery_days, order_month, and customer segments

Exploratory Data Analysis (EDA)

Univariate analysis of numerical and categorical columns

Bivariate and multivariate analysis of sales vs. returns, discounts vs. sales, ratings distribution, and delivery time impact

RFM (Recency, Frequency, Monetary) customer segmentation

Hypothesis Testing

At least 5 business hypotheses tested using statistical methods (t-tests, chi-square tests, correlation analysis)

Example: Do returned orders have significantly different average prices than non-returned orders?

Visualization

Time series plots of sales trends

Distribution plots for ratings, discounts, and delivery times

Bar charts for category-level analysis

Heatmaps for correlation between variables

Key Findings
Sales Trends: Seasonal and monthly peaks identified; specific product categories outperform during certain months.

Returns: Returned orders have lower average ratings and often longer delivery times.

Discounts: Higher discounts correlate with increased sales volume but may reduce average revenue per order.

Customer Segments: High-value customers identified via RFM analysis, offering potential for targeted marketing.

Delivery Impact: Faster delivery correlates with higher ratings and lower return rates.

Instructions to Reproduce
Clone the repository

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/ecommerce-analysis.git
cd ecommerce-analysis
Set up the environment

bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
Place your dataset

Save your CSV file as data/orders.csv inside the data/ folder.

Or set csv_url_or_path in the notebook to your public Google Sheets export URL.

Run the analysis

Open and run notebooks/01-analysis.ipynb in Jupyter Notebook or VS Code

The notebook will:

Load & clean data

Generate Data Quality Report

Run EDA and hypothesis tests

Save figures in figures/

Output insights and recommendations


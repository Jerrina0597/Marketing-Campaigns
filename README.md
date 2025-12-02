# 📊 Marketing Campaign Analysis
This project analyzes a marketing dataset to understand customer behavior and identify factors that drive customer acquisition. The work includes exploratory data analysis (EDA), data cleaning, feature engineering, hypothesis testing, and visual insights across different components of the marketing campaigns, Product,shopping behaviour etc. 

## 📁 Project Overview
Modern marketing strategies rely on understanding the four Ps: Product, Price, Place, and Promotion. In this dataset:
People: Demographics such as birth year, education, marital status, income
Product: Amount spent on wine, fruits, meat, sweet products, gold, etc.
Place: Purchases through stores, catalogs, and websites
Promotion: Campaign acceptance and complaints
The goal is to explore these factors and uncover patterns that influence campaign success and customer purchase behavior.

## 🎯 Objectives
Conduct Exploratory Data Analysis (EDA)
Perform data cleaning and missing value imputation
data used for feature engineering such as Age, Total Children, and Total Spending
Visualize distributions, detect outliers, and perform treatment
Encode categorical variables (ordinal + one-hot)
Perform hypothesis testing to evaluate claims about customer behavior
Build visual insights to support marketing decision-making

 ## 🧹 Data Preparation
### ✔ Import & Inspect Data
Validate columns like Dt_Customer, Income, and spending variables
Clean inconsistent categories in Education and Marital_Status
 ### ✔ Missing Value Imputation
Income missing values filled using average income of customers with similar education and marital status
### ✔ Feature Engineering
Total Children = Kidhome + Teenhome
Age = Current Year − Year_Birth
Total Spending = sum of all product spend categories
Derived total purchases from purchases across web, store, and catalog

## 📈 Exploratory Analysis
### 🔍 Distributions & Outliers
Boxplots and histograms for income, age, spending, and purchases
Outlier detection and treatment for skewed financial variables
### 🔍 Encodings
Ordinal encoding: Education levels
One-hot encoding: Marital status, country, and campaign responses
### 🔍 Correlation Analysis
Heatmap to understand relationships between spending, purchases, income, and campaign acceptance

## 🧪 Hypotheses Testing
Older customers prefer in-store shopping over online channels
Customers with children prefer online/cataloug purchases due to time constraints
Alternative channels cannibalize store sales
US customers outperform the rest of the world in total purchases
Each hypothesis is evaluated using statistical testing (t-tests, ANOVA, chi-square where appropriate) and supporting visualizations.

## 📊 Key Visual Insights
The project includes charts that answer:
Which products generate the most and least revenue?
Is there a pattern between customer age and last campaign acceptance?
Which country had the highest last-campaign acceptance?
How does number of children relate to total spending?
What is the education background of customers who complained in the last 2 years?

## 🛠 Tools & Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
SciPy / Statsmodels,sklearn
jupyter notebook

## 📌 Conclusion
This analysis provides actionable insights into customer demographics, spending patterns, and marketing campaign effectiveness. The findings help organizations target the right customer groups and optimize marketing strategies across the four Ps—People, Product, Place, Promotion.

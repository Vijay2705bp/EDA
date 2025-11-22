📊 Retail Sales Exploratory Data Analysis (EDA)
Dataset: Sample–Superstore.csv

🛒 Project Overview
This project performs a complete Exploratory Data Analysis (EDA) on a retail Superstore dataset. The goal is to understand how sales, profit, customers, products, and regions contribute to the business. This dataset is widely used in data analytics and data science portfolios.

This analysis uncovers important business insights like:
-Which products are profitable
-Which categories cause losses
-Which regions perform the best
-How discounts affect profits

📁 Dataset Description
Dataset file used: Sample-Superstore.csv
The dataset contains sales records across different U.S. regions.

Key columns include:
Order Date, Ship Date
Category, Sub-Category
Segment
Region, State, City
Sales
Profit
Discount
Quantity
Shipping Mode
This makes the dataset perfect for real-world retail analytics.

🎯 Objectives
The main objectives of this EDA project are:
- Clean and preprocess the dataset
- Perform univariate, bivariate, and multivariate analysis
- Understand the factors affecting sales and profit
- Identify loss-making products and regions
- Evaluate the impact of discounting
- Generate actionable business insights

🧹 1. Data Cleaning
Tasks performed:
- Checked for missing values
- Converted date columns to datetime format
- Extracted new features (Year, Month, Day)
- Removed duplicate rows
- Selected numeric columns for correlation analysis
- Cleaned column formats

📊 2. Univariate Analysis
Explored individual features:
- Sales distribution
- Profit distribution
- Count of categories and subcategories
- Shipping mode distribution
- Segment distribution
  
🔗 3. Bivariate Analysis
Compared two variables:
- Sales vs Profit
- Category vs Sales
- Region vs Profit
- Discount vs Profit
- Ship Mode vs Profit

🔎 4. Multivariate Analysis
 Correlation heatmap between numeric features
 Profit analysis grouped by category & region
 Discount effects viewed across categories
 Time trend combined with category performance

🕒 5. Time Series Analysis
 Monthly sales trend
 Yearly sales trend
 Seasonal effects

 ⭐ Key Insights
1️⃣ Technology is the most profitable category
Phones, Accessories, and Machines show strong margins.
2️⃣ Furniture is a loss-prone segment
Especially Tables and Bookcases with high discounts.
3️⃣ West region generates the highest profit
South and Central regions perform moderately.
4️⃣ Higher discounts lead to reduced profit
Negative correlation between discount and profit.

🧰 Tech Stack
 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Jupyter Notebook

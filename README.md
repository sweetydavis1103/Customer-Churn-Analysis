# Sales and Customer Behavior Analysis in California Shopping Malls

# Project Description

This project analyzes sales, customer demographics, and shopping mall attributes in California. By combining transaction data, customer details, and mall characteristics, the analysis provides insights into sales trends, customer behavior, and the impact of mall features on retail performance. The findings can help mall operators, retailers, and marketing teams make data-driven decisions to optimize sales strategies and enhance customer engagement.

# Dataset Descriptions

This analysis involves three main datasets—Sales Data, Customer Data, and Shopping Mall Data—which provide information on transactions, customer demographics, and shopping mall characteristics. Each dataset contributes unique insights when combined to analyze sales patterns, customer behavior, and the impact of mall features on sales.

# 1. Sales Data

This dataset records transaction-level details for products sold across shopping malls. Key columns include:

invoice_no: Unique identifier for each transaction.

customer_id: Identifier for the customer making the purchase.

category: Product category (e.g., Clothing, Shoes).

quantity: Quantity of each product purchased.

invoice_date: Date of transaction.

price: Price of each product purchased.

shopping_mall: Mall where the transaction took place.

Purpose: Understanding product sales across different malls and tracking how sales change over time or by category.

# 2. Customer Data

This dataset provides demographic details for each customer, including:

customer_id: Unique identifier for each customer.

gender: Customer’s gender.

age: Customer’s age.

payment_method: Preferred payment method for transactions.

Purpose: Supporting customer segmentation based on demographics (e.g., age, gender) and identifying spending patterns and payment preferences.

# 3. Shopping Mall Data

This dataset contains details of various shopping malls in California where transactions occur. Key columns include:

shopping_mall: Name of the mall.

construction_year: Year the mall was established.

area_sqm: Total area of the mall in square meters.

location: City in California where the mall is located.

stores_count: Number of stores within the mall.

Purpose: Providing context on mall attributes and enabling analysis of how mall features—such as size, store count, and location—might influence customer traffic, sales, and purchasing behaviors.

# Goal of Analysis

The goal of analyzing this data is to uncover patterns and insights that can inform decisions for optimizing sales strategies, enhancing customer engagement, and understanding the effects of mall characteristics on customer behavior. This analysis seeks to answer questions such as:

Which mall characteristics (e.g., size, age, store count) are most strongly associated with higher sales volumes?

How do customer demographics, such as age and gender, impact spending patterns across malls?

What product categories are more popular in specific malls, and how does this vary with mall characteristics?

# Methodology

# 1. Data Cleaning

Handling missing values and outliers.

Converting data types where necessary.

Standardizing column names.

# 2. Exploratory Data Analysis (EDA)

Visualizing sales distribution across different malls.

Analyzing customer spending patterns.

Identifying correlations between mall characteristics and sales performance.

# 3. Statistical Analysis

Correlation analysis between mall attributes and sales.

Hypothesis testing to determine significant factors affecting sales and customer behavior.

# 4. Forecasting & Predictive Modeling 

Applying time-series analysis for sales trends.

Building regression or classification models for customer behavior prediction.

# Tools & Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Tools: Jupyter Notebook, GitHub

# Results & Insights

Identified key factors influencing sales trends across malls.

Analyzed customer segmentation based on demographics and spending behavior.

Discovered correlations between mall attributes and sales performance.

# Conclusion & Recommendations

Malls with higher store counts and larger areas tend to generate higher sales.

Customer spending habits vary by age and gender, influencing targeted marketing strategies.

Product category popularity differs by mall characteristics, suggesting the need for customized inventory management.

# Future Scope

Expanding the dataset to include more regions.

Incorporating additional variables like promotional campaigns and seasonal trends.

Applying machine learning for advanced predictive analytics.

# Author & Acknowledgments

Author: Sweety Davis
Acknowledgments: Thanks to the data providers and the open-source community for supporting data analysis initiatives.


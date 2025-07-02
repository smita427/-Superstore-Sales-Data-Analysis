Retail Sales Analytics using Python (Superstore Dataset)

extract business insights from Superstore’s historical sales data using Python. The focus is on understanding sales trends, customer behavior, regional performance, and product profitability over time.

🎯 Objective:

To extract business insights from Superstore’s historical sales data using Python. The focus is on understanding sales trends, customer behavior, regional performance, and product profitability over time.

⸻

📦 Dataset Overview:

The dataset (superstore.xlsx) includes:
	•	Sales transactions from multiple years
	•	Customer information
	•	Product categories and subcategories
	•	Geographical data (region, country, state)
	•	Order details like shipping mode, priority, and dates

⸻

🧰 Tools & Technologies Used:
	•	Python
	•	Pandas & NumPy – data handling and aggregation
	•	Matplotlib & Plotly – data visualization
	•	openpyxl – Excel file integration

⸻

🔍 Exploratory Data Analysis (EDA)

You started with:
	•	Checking data types, missing values, and summary statistics
	•	Visualizing yearly and monthly sales trends

⸻

📈 Key Analysis & Business Questions Solved

1. 🗺 Countries with sales between 75k and 200k in 2015 (Europe & Asia Pacific)

You filtered the dataset for 2015 and specified markets, then grouped by country and summed sales. You filtered the result based on sales range.

2. 🧑‍💼 Top 20 Customers by Order Count for Selected Year and Segment

Filtered by year and segment, then grouped by customer_name, counting their orders, and sorted in descending order to get the top 20.

3. 📦 Top 3 Products in 2014 by Profit

Filtered the data for 2014, grouped by product_name, and summed profit. The top 3 profitable products were displayed using a bar chart.

4. 🏙 Top 3 Customers in Corporate Segment (California)

Filtered by segment and state, then summed sales per customer_name. Top 3 high-value customers were identified.

5. 🌎 Sales by Region for Selected Year (With Tooltip Showing Average Sale)

You grouped data by region and calculated total and average sales. A bar chart was created using Plotly, with hover tooltip showing average sales.

6. 💰 Profit by Subcategory & Category (with Avg. Profit Highlight)

Grouped data by category and sub_category, calculated total profit, and highlighted top 3 subcategories by profit within each category using a grouped bar chart.

⸻

📌 Conclusion:

This project shows how sales data can reveal insights about:
	•	Customer loyalty (top customers)
	•	Product performance over time
	•	Geographic opportunities for growth
	•	Strategic segment targeting (e.g., Corporate in California)
	•	Profit-driving subcategories within product categories



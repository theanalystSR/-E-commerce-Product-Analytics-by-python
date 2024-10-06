# -E-commerce-Product-Analytics-by-python

This project performs exploratory data analysis (EDA) on an e-commerce dataset, revealing key insights such as top-selling products, customer behavior, and sales trends. The dataset contains transaction data, including details like product descriptions, invoice dates, unit prices, quantities, and customer IDs.

Table of Contents
Overview
Technologies Used
Dataset
Key Insights
Installation
Usage
Results
License
Overview
The project focuses on analyzing an e-commerce dataset to derive meaningful insights. It covers the following aspects:

Top-selling products by total sales
Monthly sales trends
Sales distribution by country
Top customers by total spending
Calculation of the average order value (AOV)
Technologies Used
Python: Core programming language for data analysis.
Pandas: For data manipulation and cleaning.
Matplotlib: For data visualization.
Seaborn: For advanced visualizations and styling.
NumPy: For numerical calculations.
Dataset
The dataset contains 541,909 rows and 8 columns:

Column	Description
InvoiceNo	Unique invoice number for each transaction
StockCode	Product code
Description	Description of the product
Quantity	Quantity of the product sold
InvoiceDate	Date and time of the transaction
UnitPrice	Price per product
CustomerID	Unique identifier for each customer (may have missing values)
Country	Country of the customer
Key Insights
Top 10 Selling Products by Total Sales:

The product with the highest total sales is the "REGENCY CAKESTAND 3 TIER," generating £132,870.40.
Monthly Sales Trends:

Sales show peaks in December 2010 and March 2011, indicating potential seasonality in purchasing behavior.
Top 10 Countries by Total Sales:

The United Kingdom leads with the highest sales, followed by the Netherlands and Ireland (EIRE).
Top 10 Customers by Total Spending:

The highest spending customer is identified as Customer ID 14646, with a total spending of £279,489.02.
Average Order Value (AOV):

The AOV across all transactions is approximately £374.05.
Installation
To run this project locally, you'll need to have Python installed along with the required libraries. Follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ecommerce-data-analysis.git
cd ecommerce-data-analysis
Install the dependencies using pip:

bash
Copy code
pip install -r requirements.txt
Usage
Place the dataset in the project directory (if not included).
Open and run the analysis.py script using a Python IDE or Jupyter Notebook.
For example:

bash
Copy code
python analysis.py
Results
You will get outputs such as:

Bar charts for top-selling products, countries, and top customers.
Line plot for monthly sales trends.
Printed metrics like the Average Order Value and sales figures.
Sample Visualizations:
Top 10 Selling Products
Monthly Sales Trend
Top 10 Countries by Sales
License
This project is licensed under the MIT License.

# Project: Customer Analytics

## Project Overview
In this project, we want to explore the data to identify patterns of our customers behavior. The success of business depends upon how well you understand your customers. Customer Analytics is a wide area. As well as every industry will analyse customers in a different way. In this project we performed 3 analysis:
- Cohort Retention Rate Analysis
- Recency, Frequency, Monetary Value Analysis
- Customer Segmentation

Link for the jupyter notebook [Customer Analyitcs](https://github.com/firdanrastama/Customer-Analytics/blob/main/customer_analytics.ipynb)

## Dataset
[UCI Online Retail II Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

Data Set Information:
- This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers

Attribute Information:
- InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
- UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
- CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal. The name of the country where a customer resides.

## Steps of the project
- Import libraries
- Import and reading data 
- Data Cleaning
- Exploratory Data Analysis
- Cohort Retention Rate Analysis
- Recency, Frequency, Monetary Value analysis
- Customer Segmentation with KMeans

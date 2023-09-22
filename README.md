# Online Retail II
This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.

## Input:

**Website:** https://archive.ics.uci.edu/dataset/502/online+retail+ii

**InvoiceNo:** Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.

**StockCode:** Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.

**Description:** Product (item) name. Nominal.

**Quantity:** The quantities of each product (item) per transaction. Numeric.

**InvoiceDate:** Invice date and time. Numeric. The day and time when a transaction was generated.

**UnitPrice:** Unit price. Numeric. Product price per unit in sterling (Â£).

**CustomerID:** Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.

**Country:** Country name. Nominal. The name of the country where a customer resides.

## Output
Predicts the total sales per customer.

## Data mining function
Regression and predict

### Steps
- Reading data

- Fix Data Problems:
{
* Dealing with Missing values
* Remove Description column and set null values in Customer ID
* Removing duplicated rows
* Replace invalid data in Quantity and Price columns
* Cleaning Country column
* Create new column to Split Invoice into cancel or not
* Check duplicates
}

- Create new features

- Merge DataFrame and Groupby tables

- Preprocessing 

- Splitting data

- Extract numerical features and categorical Features

- Tuning Pipeline

- Deep learning model

# US Supermart Data Analysis Project

## Project Overview
This project involves analyzing the **US Supermart dataset** using **Python** and **Jupyter Notebook**. The dataset consists of **transactional data**, including **order details, customer information, product categories, and shipping details**. The objective of this project is to **clean the data, explore key insights, and visualize patterns** using Python libraries like **Pandas, Matplotlib, and Seaborn**.

## Dataset Description
The dataset contains **9,426 rows** and **24 columns**, with attributes such as:

- **Row ID**
- **Order Priority**
- **Discount**
- **Unit Price**
- **Shipping Cost**
- **Customer ID & Name**
- **Ship Mode**
- **Customer Segment**
- **Product Category & Sub-Category**
- **Region, State, City, Postal Code**
- **Order Date & Ship Date**
- **Profit**
- **Quantity Ordered**
- **Sales**

## Data Cleaning
- **Handled missing values** by replacing missing **Product Base Margin** values with the **mean**.
- **Verified and confirmed** that all other columns had no missing data.

## Exploratory Data Analysis (EDA)

### 1. **Order Priority Distribution**
The dataset contains the following **order priorities**:

- **High:** 1,970 orders
- **Low:** 1,926 orders
- **Medium:** 1,844 orders
- **Critical:** 1,805 orders
- **Not Specified:** 1,881 orders

*A bar chart was plotted to visualize the distribution.*

### 2. **Shipping Mode Analysis**
The dataset includes three **shipping modes**:

- **Regular Air:** 74.64% of shipments
- **Delivery Truck:** 13.61% of shipments
- **Express Air:** 11.74% of shipments

*A pie chart was used to represent the proportion of each shipping mode.*

### 3. **Yearly Order Trends**
The order distribution by year:

- **2013:** 3,054 orders
- **2012:** 2,241 orders
- **2011:** 2,179 orders
- **2010:** 1,952 orders

*The dataset shows an increasing trend in order volume over the years.*

### 4. **Top 5 States by Order Volume**
- **California:** 1,021 orders
- **Texas:** 646 orders
- **Illinois:** 584 orders
- **New York:** 574 orders
- **Florida:** 522 orders

*This highlights that **California** has the highest number of orders.*

## Visualizations
The project includes multiple **visualizations** to support insights, such as:

- **Bar charts** for order priorities and top states
- **Pie charts** for shipping modes
- **Count plots** to analyze categorical distributions

## Tools & Libraries Used
- **Python**
- **Jupyter Notebook**
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib & Seaborn** for data visualization

## Conclusion
- **Regular Air** is the most used shipping method, indicating its popularity among customers.
- **High-priority orders** are common, showing a significant demand for urgent deliveries.
- **California** leads in order volume, suggesting a major market presence in the state.
- **Sales have increased** over the years, reflecting business growth.



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

![Order Priority Distribution](https://github.com/user-attachments/assets/e6e12f2a-fcb0-43f6-a3e9-f889a77486bc)


### 2. **Shipping Mode Analysis**
The dataset includes three **shipping modes**:

- **Regular Air:** 74.64% of shipments
- **Delivery Truck:** 13.61% of shipments
- **Express Air:** 11.74% of shipments

![SHIP MODE SPLIT](https://github.com/user-attachments/assets/2cb38803-e488-4832-a2af-39ad336de142)


### **Shipping MOode Based On  Product Category**
![SHIP MODE ON BASE OF CATEGORY ](https://github.com/user-attachments/assets/5011b067-af3b-467b-b8de-1c2a8e78de16)


### 3. **Yearly Order Trends**
The order distribution by year:

- **2013:** 3,054 orders
- **2012:** 2,241 orders
- **2011:** 2,179 orders
- **2010:** 1,952 orders

![DISTRIBUTION OF OFFICE SUPPLY BY SUB CATEGORY](https://github.com/user-attachments/assets/75160dd4-c8c1-4f2f-a32d-3e7c9dde1220)


### 4. **Top 5 States by Order Volume**
- **California:** 1,021 orders
- **Texas:** 646 orders
- **Illinois:** 584 orders
- **New York:** 574 orders
- **Florida:** 522 orders

*This highlights that **California** has the highest number of orders.*

### 5.**Customer Segments Driving the Most Business Revenue**
![CUSTOMER SEGMENT ](https://github.com/user-attachments/assets/99cb888c-88fa-4bcf-adb7-0a555b7daf74)


## Visualizations
The project includes multiple **visualizations** to support insights, such as:

- **Bar charts** for order priorities and top states and customer segment for most business revenue
- **Pie charts** for shipping modes
- **Count plots** to analyze categorical distributions and shipping mode categorical analysis

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



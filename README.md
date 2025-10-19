# Maven Mega Mart: Retail Sales Analysis

## Project Overview
This project involves an in-depth analysis of transactional data from Maven Mega Mart, a fictional retail company. The primary goal is to uncover insights into customer purchasing behavior, identify top-performing products, and analyze the effectiveness of discount strategies.

---

## Data Source
The dataset was provided as part of a mid-course project from Maven Analytics and consists of two files:
- `project_transactions.csv`: Contains detailed transaction records.
- `product.csv`: Contains product metadata.

---

## Key Questions and Findings

1.  **Overall Performance:**
    * Total Sales: **$6.67M**
    * Total Quantity Sold: **216.7M units**
    * Overall Discount Rate: **20.8%**

2.  **Household (Customer) Analysis:**
    * Identified the top 10 households by both sales value and total quantity purchased, highlighting key customer segments.
    * Household `1023` was the top customer by both sales value ($38,319) and quantity.

3.  **Product Analysis:**
    * The product with `PRODUCT_ID` 6534178 (Gasoline) was the highest-selling item by a significant margin.
    * Analysis revealed that the **top 10 selling products had a lower average discount rate (18.5%)** compared to the overall average (20.8%), suggesting that high sales volume for these items is not primarily driven by discounts.

---

## Tools and Libraries
- **Language:** Python
- **Libraries:** Pandas for data manipulation and analysis, Matplotlib for data visualization.
- **Environment:** Jupyter Notebook

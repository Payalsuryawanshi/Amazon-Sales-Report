
# Amazon Sales Dashboard
### Dashboard Link : https://svvvindore-my.sharepoint.com/:u:/g/personal/20100btit07703_svvvindore_onmicrosoft_com/EWgcIolTQixGuA2Ch1cK33IBx9hQTVYszEGdXgRhAW0s5w?e=nIrXFX

## Overview

This Amazon Sales Dashboard provides a comprehensive analysis of sales transactions from the provided dataset. It offers key insights into sales performance, product popularity, fulfillment efficiency, and customer behavior, all visualized through interactive charts and graphs. The dashboard is designed to help stakeholders make data-driven decisions to optimize sales strategies, improve customer satisfaction, and enhance overall business performance.

## Key Features

- **Sales Overview:** Visualizes overall sales trends, identifying patterns and peak periods.
- **Product Analysis:** Breaks down the distribution of product categories, sizes, and quantities sold to highlight top-selling items.
- **Fulfillment Analysis:** Examines the effectiveness of different fulfillment methods, including delivery speed and order completion rates.
- **Customer Segmentation:** Analyzes customer buying behavior and segments them based on geographical location, purchase frequency, and recency.
- **Geographical Analysis:** Maps out sales data across various regions to pinpoint high-performing areas and identify potential growth opportunities.
- **Business Insights:** Provides actionable recommendations to optimize inventory, enhance fulfillment processes, and target key customer segments.

## Technology Used

- **Power BI:** Utilized for data cleaning, transformation, and creating interactive visualizations and dashboards.
- **SQL & Python:** Employed for initial data processing, cleaning, and exploratory analysis.

## Purpose

The Amazon Sales Dashboard is designed to assist business stakeholders in understanding complex sales data through an intuitive visual interface. By leveraging this tool, decision-makers can drive growth, improve operational efficiency, and enhance customer satisfaction based on data-driven insights.

Here’s a detailed breakdown of the steps involved in data cleaning using Power Query Editor in Power BI:

### **Steps in Data Cleaning Using Power Query Editor**

1. **Loading Data into Power Query:**
   - **Import Data:** Open Power BI and import your dataset (e.g., CSV, Excel).
   - **Open Power Query Editor:** After importing, click on the “Transform Data” button to open the Power Query Editor.

2. **Remove Unnecessary Columns:**
   - **Select Columns:** Identify and select columns that are not required for analysis.
   - **Remove Columns:** Right-click on the selected columns and choose “Remove Columns” to delete them from the dataset.

3. **Handle Null or Missing Values:**
   - **Filter Null Values:** Identify columns with null values.
   - **Remove Rows or Replace Values:** Depending on the context:
     - **Remove Rows:** If the null values represent insignificant data, remove those rows by right-clicking and selecting “Remove Rows.”
     - **Replace Nulls:** If it’s appropriate to replace nulls with a placeholder or an average value, use the “Replace Values” function.

4. **Remove Duplicates:**
   - **Select Columns:** Choose columns that should not have duplicate values (e.g., Order ID).
   - **Remove Duplicates:** Right-click and select “Remove Duplicates” to delete any redundant rows.

5. **Format Data Types:**
   - **Set Data Types:** Ensure each column is assigned the correct data type (e.g., date, text, number).
   - **Convert Data Types:** Click on the column header, and choose the appropriate data type from the drop-down menu.

6. **Trim and Clean Data:**
   - **Trim:** Remove extra spaces from text data using the “Trim” function.
   - **Clean:** Remove non-printable characters by selecting the “Clean” function.

7. **Handle Inconsistent Data (Standardization):**
   - **Replace Values:** Standardize inconsistent data entries (e.g., “NY” vs. “New York”) using “Replace Values.”
   - **Custom Column Logic:** For more complex transformations, add a custom column with logic to standardize the data.

8. **Date and Time Transformations:**
   - **Convert Date Formats:** Ensure all date columns are in a consistent format by using the “Change Type” or “Transform” functions.
   - **Extract Date Parts:** Extract components like day, month, and year using the “Add Column” tab, then select “Date” to access date parts.

9. **Filter Data:**
    - **Apply Filters:** Use filters to remove irrelevant data (e.g., incomplete orders, future dates).
    - **Conditional Filtering:** Use conditional logic to keep only the rows that meet specific criteria.

10. **Group Data:**
    - **Group by Function:** If necessary, group data by one or more columns to summarize or aggregate it (e.g., total sales per month).

11. **Add Calculated Columns:**
    - **Custom Columns:** Create new columns based on calculations or logic (e.g., Sales Amount = Quantity * Price).
    - **Use M Language:** For advanced transformations, use the M language in the “Custom Column” formula box.

12. **Sort Data:**
    - **Sort Rows:** Arrange your data by one or more columns in ascending or descending order using the “Sort Ascending/Descending” function.

13. **Rename Columns:**
    - **Column Names:** Rename columns to more meaningful names by double-clicking on the column header.


These steps ensure that the data is well-prepared for analysis, making the insights you derive more accurate and actionable.

# Snapshot of Dashboard 
![Dashboard_upload](https://github.com/Payalsuryawanshi/Amazon-Sales-Report/blob/main/Screenshot%20(399).png)


![Dashboard_upload](https://github.com/Payalsuryawanshi/Amazon-Sales-Report/blob/main/Screenshot%20(400).png)


![Dashboard_upload](https://github.com/Payalsuryawanshi/Amazon-Sales-Report/blob/main/Screenshot%20(401).png)



### **Key Insights from Amazon Sales Analysis**

1. **Sales Patterns:**
   - **Peak Order Days:** Orders are highest on Tuesdays and Saturdays, indicating peak shopping activity on these days.
   - **Seasonal Trend:** Maximum orders occur in April, May, and June, highlighting a strong sales trend during the summer season.

2. **Product Performance:**
   - **Top Revenue Driver:** T-shirts contribute significantly to overall sales, driving the highest revenue.
   - **Popular Sizes:** Medium and Large sizes dominate sales, reflecting customer preferences.
   - **Top-Selling Category:** T-shirts are the most popular product, with approximately 42,000 units sold.

3. **Fulfillment Analysis:**
   - **Preferred Fulfillment Method:** Amazon's fulfillment service is the most commonly used, accounting for nearly 69% of all orders.
   - **Fulfillment Efficiency:** Orders fulfilled by Amazon are associated with a higher volume of product shipments.

4. **Customer Segmentation:**
   - **Loyal Customers:** Customers with low recency, high frequency, and large size purchases are the most loyal and valuable, frequently buying and spending significantly.
   - **Infrequent Buyers:** Customers with low recency, low frequency, and smaller purchases tend to buy less often and spend less.
   - **Dormant Customers:** Customers with high recency, low frequency, and smaller purchases haven't bought in a while and contribute less to sales.

5. **Geographical Insights:**
   - **Top Cities:** Bengaluru and Hyderabad have the highest customer concentration, contributing significantly to sales.
   - **Regional Sales:** Southern regions like Maharashtra, Karnataka, Telangana, and Tamil Nadu dominate total sales.
   - **Growth Opportunities:** The central region shows minimal contribution, while eastern regions present untapped potential for growth and expansion.



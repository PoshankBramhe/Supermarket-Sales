# Supermarket-Sales

<h2>Overview</h2>
This README provides a step-by-step guide for cleaning, exploring, visualizing, and analyzing a dataset using Excel. The dataset contains information about orders, including Order ID, Date, Product, Category, Price, and Quantity.<br>

<h3>Data Cleaning and Exploration</h3>
Open the Dataset in Excel:<br>

Open the dataset in Excel by importing the CSV or Excel file.<br>
Remove Duplicate Rows:<br>

Use Excel's "Remove Duplicates" feature to eliminate any duplicate rows based on the "Order ID."<br>
Calculate and Add "Revenue" Column:<br>

Create a new column named "Revenue" that calculates the product of Price and Quantity for each row using the formula =Price*Quantity.<br>
Create Pivot Table:<br>

Generate a pivot table to summarize total revenue and quantity sold for each product and category.<br>
Place "Product" and "Category" in Rows.<br>
Place "Revenue" and "Quantity" in Values, summarizing by sum.<br>
<h3>Data Visualization</h3>
Bar Chart for Total Revenue by Product Category:<br>

Create a bar chart to visualize the total revenue for each product category.<br>
Line Chart for Revenue Trend Over Months:<br>

Generate a line chart to display the trend of total revenue over the months.<br>
Use "Date" on the x-axis and sum of "Revenue" on the y-axis.<br>
Scatter Plot for Price vs. Quantity:<br>

Create a scatter plot to show the relationship between price and quantity for products.<br>
Use "Price" on the x-axis and "Quantity" on the y-axis.<br>
<h3>Advanced Analysis</h3>
Calculate Average, Minimum, and Maximum Price by Category:<br>

For each product category, calculate the average, minimum, and maximum price using Excel functions.<br>
Identify Top 5 Products with Highest Revenue:<br>

Sort the dataset based on "Revenue" in descending order and identify the top 5 products.<br>
Calculate Total Revenue for Each Month:<br>

Extract the month from the "Date" column and calculate total revenue for each month.<br>
<h3>Conditional Formatting</h3>
Highlight Products with Quantity Above Threshold:<br>
Apply conditional formatting to highlight products in the pivot table with a total quantity above a specified threshold (e.g., 50).<br>
<h3>Filtering and Sorting</h3>
Filter Products and Categories:<br>

Apply filters to the "Product" and "Category" columns to view specific products or categories.<br>
Sort Data Based on Total Revenue:<br>

Sort the data based on the "Total Revenue" column in descending order to identify the most profitable products.<br>

# Power-BI-Assignment-2
 DAX &amp; Data Visualization 
Imported the following three CSV files into Power BI:
1. List of Orders.csv
2. Order Details.csv
3. Sales target.csv
create relationships between the three tables:
- List of Orders
- Order Details
- Sales target
Created three calculated columns in the Order Details table.
1.Combined Category and Sub-Category into a single column.
2.Calculated revenue by multiplying Amount by Quantity.
3.Categorized sales into Above Average and Below Average based on the Amount value.
Created three DAX measures to calculate key business metrics.
1.Order Count
2.Average Profit in Delhi
3.Average Profit in Delhi
Created the following visualizations using Power BI.
1.Visualization: Clustered Column Chart
Axis: Category
Values: Actual Sales and Sales Target
2.Max Profit Margin by Sub-Category
- Visualization: Donut Chart
- Legend: Sub-Category
- Values: Max Profit Margin
3. Monthly Sales Trend
- Visualization: Line Chart
- X-axis: Order Date (Month)
- Y-axis: Actual Sales
4. Comparison of Profit and Quantity by Sub-Category
- Visualization: Scatter Chart
- X-axis: Quantity
- Y-axis: Profit
- Details: Sub-Category
5. Comparison of Total Sales Amount and Target
- Visualization 1: Card – Total Sales Amount
- Visualization 2: Card – Sales Target
- Visualization 3: Table – Minimum Target by Category
Used a Table visual because in my lap multi row is not available
6. Sales Performance Matrix
- Visualization: Matrix
- Rows: Category
- Columns: Month
- Values: Actual Sales and Sales Target
7. Geographic Sales Analysis
- Visualization: Map
- Location: City
- Bubble Size: Actual Sales
- some times location not showing in my lap because of security  location is not working properly
8. Sales Distribution by Sub-Category
- Visualization: Treemap
- Group: Category
- Details: Sub-Category
- Values: Actual Sales
9. Order Count Analysis by State
- Visualization: Funnel Chart
- Category: State

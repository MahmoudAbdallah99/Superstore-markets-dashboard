# Superstore-markets-dashboard

First, it's about dataset of global markets called superstore, it's made up of 3 CSV sheets orders, returns and people.

Implementation steps:
1) Connecting Database with Power BI Desktop.
2) Analyzing the tables and relations.
3) Data Cleaning using Power Query Editor with DAX (Data Analysis Expressions). 
    - Add two columns Delivery days (shipped date - order date) and year from date to orders sheet.
    - Add the return orders column to returns sheet and using an if statement to convert it from yes or no to 0 or 1 to sum all returns.

4) Use power bi to visualize the data
    - Map of sales by region.
    - Pie chart of sales by market.
    - Pie chart of sales by segment.
    - Stacked bar chart of the top 6 profit and loss products
    - Stacked bar chart of the top 10 clients.

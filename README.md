# Zomato-Restaurant-Analysis
# Zomato Restaurant Data Analysis Project

This project involves analyzing Zomato restaurant data using advanced Excel functions, SQL queries, and creating interactive dashboards with Power BI and Tableau. The objectives of the project include:

- Building a country map table
- Creating a calendar table using the `datekey` column and adding columns such as:
  - Year
  - Month number
  - Full month name
  - Quarter (Q1, Q2, Q3, Q4)
  - Year-Month (YYYY-MMM)
  - Weekday number
  - Weekday name
  - Financial month (April = FM1, May = FM2 … March = FM12)
  - Financial quarter (based on financial months)
- Finding the number of restaurants by city and country
- Analyzing restaurant opening trends by year, quarter, and month
- Counting restaurants by average ratings
- Creating price range buckets and finding the number of restaurants in each bucket
- Calculating the percentage of restaurants offering table booking and online delivery options
- Developing charts based on cuisines, city, ratings, and other relevant parameters

The project demonstrates the use of Excel, SQL, Power BI, and Tableau to extract insights and visualize trends in the restaurant industry based on location, ratings, price ranges, and other parameters.

## Tools and Techniques Used

### Excel

To achieve the objectives, the following advanced Excel functions and techniques were used:

- **SUMIFS** and **COUNTIFS** functions to extract and count data based on specific criteria.
- **PivotTables** and **PivotCharts** to summarize and analyze data.
- **Conditional formatting** to highlight key insights in the data.
- **Report connections** to link multiple PivotTables and charts to a single slicer for dynamic filtering.
- **VLOOKUP** and **INDEX-MATCH** functions to merge data from different tables.
- **DATE** and **YEAR** functions to extract information from date fields.

### SQL

The following SQL queries and techniques were applied to extract relevant data from the Zomato dataset:

- **SELECT** to retrieve specific columns.
- **FROM** to specify the tables.
- **WHERE** to filter data based on conditions.
- **GROUP BY** to group data by specific columns.
- **ORDER BY** to sort data in ascending or descending order.
- **HAVING** to filter data based on aggregated values.
- **Window functions** such as **ROW_NUMBER**, **RANK**, and **DENSE_RANK** to perform calculations on subsets of data.
- **Date functions** like **DATEADD**, **DATEDIFF**, and **DATEPART** to extract and manipulate date fields.

### Power BI

For data visualization and analysis, Power BI was used with the following features:

- **Data modeling** to establish relationships between tables and calculated columns.
- **Measures** and **DAX formulas** to perform calculations.
- **Visualizations** like tables, charts, and maps for data display.
- **Slicers** and **filters** for dynamic filtering of data.
- **Drill-through functionality** to navigate between different levels of data.

### Tableau

Tableau was also used to create interactive dashboards. Key features include:

- **Data blending** to combine data from multiple tables.
- **Calculated fields** to perform data calculations.
- Use of **dimensions** and **measures** to organize and analyze the data.
- **Visualizations** such as maps, charts, and tables for data display.
- **Filters** and **parameters** for dynamic filtering.

## Key Insights

This project provides valuable insights into restaurant industry trends related to:

- **Location**: Number of restaurants by city and country.
- **Opening trends**: Restaurant openings by year, quarter, and month.
- **Ratings**: Distribution of restaurants based on average ratings.
- **Price range**: Categorization of restaurants into price buckets.
- **Services offered**: Percentage of restaurants providing table booking and online delivery services.

## Conclusion

This project showcases how to leverage Excel, SQL, Power BI, and Tableau for data analysis and visualization. It provides a useful resource for those interested in understanding the restaurant industry and learning how to apply these tools in a real-world data analysis project.

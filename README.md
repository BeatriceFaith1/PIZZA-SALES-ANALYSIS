# PIZZA-SALES-ANALYSIS
Link to Dashboard: https://app.powerbi.com/view?r=eyJrIjoiZGFmMjI5MGEtZTIzNS00MTVlLTk2MGUtODcwMDAyZTE3YmMwIiwidCI6ImViMzE2NWVhLWM5ZmMtNDIwZi04ZmE1LTBmZWNiYTYwYWJhMCJ9


In today’s competitive food and beverage industry, businesses must gain clear insights into their sales performance, customer preferences, and product success to drive growth and optimize operations. The primary objective of this project is to analyze pizza sales data to identify key trends, including the most popular pizza categories, ingredients, and sizes, as well as revenue performance across different months and quarters. By providing actionable insights through an interactive Power BI dashboard, this analysis enables businesses to make informed decisions to increase revenue and improve customer satisfaction.

2. Methodology

2.1 Data Source

The dataset for this project was sourced from Kaggle and comprised four relational tables: the Pizza Table, Pizza Type Table, Order Details Table, and Order Date Table. These tables provided comprehensive data on pizza types, sales orders, ingredients, and order dates, forming the foundation for analysis.

2.2 Data Cleaning Procedures

The data cleaning process was carried out in Power BI Power Query Editor to ensure accuracy and usability. First, all four relational tables were imported into Power BI, where duplicate records were identified and removed to eliminate redundancy. Measures such as Total Quantity Sold and Total Revenue were created using DAX (Data Analysis Expressions) to enable quantitative analysis. A custom Date Table was built using DAX to introduce time-based dimensions, including Year, Quarter, and Month.

To resolve Power BI’s default alphabetical sorting of months, two new columns were created: Month Name for the month labels and Month Sort for their numerical order. The ‘Sort Column’ feature under the Modeling section was used to align months chronologically from January to December. Unnecessary columns were removed to clean up the dataset, ensuring streamlined and efficient data processing. This process prepared the data for accurate visualizations and insights.


2.3 Data Modelling

The four relational tables were modeled using one-to-many relationships to integrate the data effectively. The Pizza Table was connected to the Pizza Type Table using the pizza type ID, while the Order Details Table and Order Date Table were linked through the order date. This relational model allowed seamless aggregation of sales data, enabling drill-down analysis across pizza types, time dimensions, and sales quantities. The rationale for these relationships was to facilitate efficient query performance and provide a clear data structure for analysis.

2.4 Data Analysis and Visualisation

The analysis and visualizations were developed using Power BI to uncover meaningful insights and trends. A line chart for Total Revenue by Month was created to analyze revenue patterns over time, revealing seasonal fluctuations. Notably, revenue peaked mid-year in July, while months like February and October recorded significant declines. A donut chart showing revenue distribution by Pizza Categories (Classic, Supreme, Veggie, and Chicken) highlighted that the Supreme category generated the largest share of revenue, accounting for 30.03% of total sales.


To understand ingredient popularity, a bar chart for the Top 5 Popular Ingredients showcased key combinations like Tomatoes and Red Peppers as the most frequently sold ingredients. Similarly, the Top 5 Bestselling Pizzas chart identified the leading performers, with the Thai Chicken pizza being the top choice, contributing the highest revenue. A pie chart for Total Quantity Sold by Size revealed that Large (L) pizzas dominated sales, accounting for 38.24% of the total, while other sizes like Medium and Small followed closely.


3. Insights and Recommendations

The analysis provided the following key insights and business recommendations:


1. July recorded the highest revenue, suggesting strong demand during mid-year, while February and October showed weaker sales performance.
Recommendation: Introduce mid-year promotional campaigns to capitalize on the natural peak in demand and implement targeted marketing strategies to boost sales during low-performing months.
Pizza Categories and Ingredients:

Insights

2. Supreme pizzas accounted for 30% of total sales, making them the most attractive category. Ingredients like Tomatoes and Red Peppers were the most popular combinations.
Recommendation: Promote Supreme pizzas through combo deals or discounts and introduce new variants that incorporate popular ingredients to enhance customer interest.


3. Large-sized pizzas accounted for the largest share (38.24%) of total quantity sold.
Recommendation: Focus on marketing large pizzas as value-for-money options for group meals and offer upsell opportunities for customers ordering smaller sizes.


4.  The Thai Chicken pizza emerged as the top-performing product.
Recommendation: Highlight bestselling pizzas like the Thai Chicken in advertisements and menus while exploring similar flavor profiles to introduce new offerings.


Conclusion

This project successfully analyzed pizza sales data to identify critical trends, customer preferences, and revenue patterns. By leveraging Power BI’s capabilities for data cleaning, modeling, and visualization, the project delivered an interactive dashboard that provides actionable insights for business growth. The recommendations, if implemented, can help optimize sales strategies, improve product offerings, and maximize revenue potential in a competitive market.


# Adidas 2020-2021 Sales Analysis 
## Project objective
This project showcases a comprehensive sales analysis of Amazon data using Power BI. I built an interactive dashboard that examines sales performance across multiple dimensions, including product categories, regions and dates among other factors. The goal was to come up with visual analytics of sales between 2020 and 2021 to support strategic decision-making.


## Dataset used in this project
- <a href= 'https://github.com/MtitiTendai/Amazon-Sales-Analysis-Dashboard/blob/main/Adidas%20US%20Sales%20Datasets.xlsx'>Sales Data</a>

## Problem Statement (KPIs)
<p><b> a.) Total Sales by Month: </b><br>
            - Visualise the monthly distribution of total sales to identify peak periods (using Area Chart).</p>
<p><b> b.) Total Sales by State: </b><br>
       - Geographical representations of total sales across different states (using Field Map).</p>
<p><b> c.) Total Sales by Region: </b><br>
       - Contribution of different regions to total sales (using Donut Chart).</p>
<p><b> d.) Total Sales by Product: </b><br>
       - Analyse sales distribution among various Adidas producst (using Bar Chart).</p>
<p><b> e.) Total Sales by Retailer: </b><br>
       - Visualise the contribution of different retailers to total sales (using Bar Chart).</p>

## Methods used
Data Modeling – I built a star schema model where the Sales table acted as the central fact table, and I connected dimension tables such as Products, Regions, Retailers, and Time. I established one-to-many relationships using Power BI's model view to allow proper filtering and slicing between visuals. I also included a Date Table to support time-based calculations like year-to-date and month-to-date sales.

Data Cleaning and Preparation – In this stage, I used Power Query Editor to clean and structure the raw Adidas data. I removed duplicate entries, filtered out irrelevant rows, and changed column data types to ensure proper analysis. I also split columns (like splitting product codes), replaced empty values, and renamed fields for clarity, making the data consistent and analysis-ready.

DAX Measures and Calculations – I created DAX measures to calculate key performance indicators such as Total Sales, Units Sold, and Operating Profit. I used the DIVIDE() function for accurate calculations like Price per Unit and Operating Margin. For more advanced analysis, I implemented time intelligence functions like TOTALYTD() and SAMEPERIODLASTYEAR() to compare performance across periods. I also used RANKX() to rank products and retailers based on their sales performance.

Visualizations and Dashboard Design – I used various Power BI visuals to communicate insights effectively. KPI cards showed high-level figures like Total Sales and Profit. A line chart displayed monthly sales trends, while bar and donut charts revealed sales by product, region, and retailer. I also used a map visual to highlight sales distribution across U.S. states. The layout was organized with a clean color theme and interactive design for better user experience.

Filters and Interactivity – To make the dashboard dynamic, I added slicers for Region, Product Category, and Date. These slicers allow users to explore the data based on their preferences. I also enabled cross-filtering between visuals and included custom tooltips to give users detailed information when hovering over a chart or data point. This improved the interactivity and storytelling of the dashboard.

Insights and Recommendations – From the analysis, I observed that Adidas had peak sales in July, while February and October were low-performing months. The West region and retailers like West Gear and Foot Locker led in total revenue. Products such as Men’s Street Footwear and Women’s Apparel performed exceptionally well. I recommended boosting marketing in off-peak months, investing in underperforming regions, and improving e-commerce performance on platforms like Amazon.

# Visulisation Process for Dashboard

KPI Cards for high-level metrics (sales, units, margin)

Line/Area Charts to show monthly sales trends

Donut Chart for region-wise sales breakdown

Map Visual (Choropleth) to display sales distribution by U.S. states

Bar Charts for top-performing products and retailers

I applied consistent color themes, used custom tooltips, and ensured the layout followed best practices in readability and visual storytelling.


## The Dashboard
- <a href= 'https://github.com/MtitiTendai/Amazon-Sales-Analysis-Dashboard/blob/main/dashboard.png'>Dashboard</a> <br><br><br>
![dashboard](https://github.com/user-attachments/assets/be94b054-2621-49b9-8edb-31b73d229090)

## Analyis and Recommendations
According to the analysis I conducted on Adidas sales data, the company generated $900 million in total revenue, selling 2 million units at an average price of $45 per unit. I discovered that Adidas maintained a strong 42% operating margin, resulting in a profit of $332 million. From the monthly trend, I noticed that sales peaked in July, while the lowest figures were recorded in February and October, highlighting clear seasonal patterns that Adidas could target with focused marketing strategies during off-peak months.

As I further analyzed the data, I found that the West region was the highest-performing, contributing $270 million, while regions like the Midwest and South had relatively lower sales. I also identified that Men’s Street Footwear and Women’s Apparel were the best-selling product categories, indicating strong customer demand in those segments. In terms of retail performance, I observed that West Gear and Foot Locker led in sales, whereas platforms like Amazon and Walmart showed lower contributions, despite their broad online reach.

Based on these insights, I recommend that Adidas strengthen its efforts in underperforming regions and invest more in high-demand product categories. The company should also consider launching seasonal campaigns to boost sales during slower months. Additionally, enhancing online retail strategies, especially on platforms with lower performance, could help expand Adidas’s market reach and improve overall sales performance.



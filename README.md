# Tediumless_Aeye
Analytics, Analysis and AI Convergence 
# Sales Trend Analysis and Forecasting

## Project Overview
This project aims to transform the sales and customer data of a Client into a series of compelling, actionable Microsoft Power BI visuals. The exercise aimed to provide the company's executive team with insightful and targeted information that could drive strategic decision-making at the highest level. 

## Objectives
1. Create a variety of visualizations, including a table, column chart, line chart, and Key Performance Indicators (KPIs), to represent complex sales and customer data in a digestible format.
2. Customize these visuals by setting specific colors and adding tooltips, enhancing the user experience and accessibility of the data.
3. Implement forecasting functionalities on the line chart, empowering the executives to anticipate future sales trends and take proactive measures.
4. •	Integrate a Q&A visual into the report, enabling the executive team to query the data directly and receive timely insights.

## Data Collection
- Gathered historical sales data from Client's sources.
- Ensured data includes relevant fields such as Sales dates, Product categories, Quantities sold, Product id, Product Name, Order ID, Order Status, Order Total, Product Weight, Sum of Order Total and Revenue.

## Data Preparation and Cleaning
1. Remove duplicates and irrelevant data points.
2. Handle missing values.
3. Standardize date formats.

## Data Modelling
Create a Star-schema

## Import and Load Cleaned data (Sales & Customer tables) into Power BI Desktop and create visualizations

1.              Table Visual
Table visualization serves as a quick reference, showcasing what products are selling and where it’s at in the delivery pipeline paramount.
i. On blank canvas, Select the Table icon to create an empty table visualization on the canvas.
ii. Select the Sales table to expand it and view its fields.
iii. Drag and drop Product ID from the Data pane to the Columns well in the Visualizations pane and drag Product Name, Order ID, Order Status, and Order Total into the same Columns well.
iv. Format table visual and change its appearance.

2.            Column Chat
What sold is important however, it's crucial to know what’s selling dominantly and what’s not leaving the warehouse. A column chart instantly shows which product categories at are revenue generators and which need a strategic revisit.
i. Select the Clustered Column chart icon in the Visualizations pane.
ii. Make Product Category from the Sales table the X-Axis.
iii. Make Order Total from the same Sales table the Y-Axis well.
iv. Format column chart to change its appearance, using Dark Blue: #2D386D gives it a unified look.
v. Drop Order Quantity and Product Weight fields from the Sales table into the Tooltips field well.
vi. Sort Sum of Order Total in ascending order.
* Observation: The Order Total for Kids Bikes is $500, making it the product category with the lowest overall sales.

  3.                Line Chart
 Sales peak drop times will help Client rejig it's seasonal strategies and the Line Chart will help necessary context.
 i. Select the Line chart icon in the Visualizations pane. 
 ii. Make OrderDate from the Sales the X-Axis.
 iii. and Order Total and the Y-Axis.
 
## Create KPI Visualization Using Power BI 

KPIs offer performance check into questions like “Are we hitting our sales goals? How expansive is our customer reach? How are we tracking our goals of being a global player?” These KPIs provide reality check and inspiration rolled into one.
i. Select the KPI icon in the Visualizations pane.
ii. Drop Order Total from the Sales table to the Value field well.
iii. Drop OrderDate from the Sales table to the Trend Axis field well.
iv. To get the count of the number of UNIQUE CUSTOMERS that have made a purchase; Drag Customer ID from the Customers table to the Indicator field well and the OrderDate from the Sales table to the Trend Axis.
v. To get the number of UNIQUE COUNTRIES that customers are located; Drag City from the Customers table to the Indicator field well and the OrderDate from the Sales table to the Trend Axis. 
vi. Adding 2 more KPIs; repeat steps i - iii

## Setup Sales Forecasting Using Power BI
Forecasting enables the prediction of future trends based on historical data helping in making data-driven decisions for the future.
i. Using the line chart visualization earlier created to explore the related options in the Visualizations.
ii. Select the Analytics tab, represented by a magnifying glass icon.
iii. Select the Forecast option and add a forecast line by toggling the switch.
iv. Adjust Seasonality and Confidence interval parameters. *Seasonality is useful because Client's data has a repeating pattern, setting this to 12 is useful to account for monthly seasonality.
* Adjust the confidence interval value to 99% for 95%, the default value to ensure the forecast is as confident as possible.
V. Apply the changes made to the configured parameters.
Observation: The lowest order total for Q1 in 2023. 


## Configuring Q&A
This transformative feature allows Client to interact with the data in a conversational manner and generate insights on-the-fly.
1.	Select the Q&A icon and get it on the canvas.
2. Run prompt queries to get insights about the data:
i. Which customer City has the lowest average Order Total? 
ii. Which Product Category has the highest average Order Quantity?
iii. Which Product Subcategory has the highest Product Weight? 

## Conclusion
This project created compelling Power BI reports, unlocked the hidden stories within Client's vast data, empowering decision-makers to act swiftly, strategically, and substantively. Every visualization and every KPI could be the butterfly effect that drives the revolution the Client needs even as this project turned numbers into narratives that can drive business outcomes.

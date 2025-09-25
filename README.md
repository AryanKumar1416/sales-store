# sales-store
Project Description
This project performs an in-depth analysis of the Superstore dataset to identify key sales and profit trends, analyze geographical performance, investigate reasons for negative profits in specific regions, and forecast future sales. The analysis utilizes Python libraries such as pandas for data manipulation and matplotlib and seaborn for visualization. Time series forecasting is performed using the Prophet library.

Data Source
The dataset used for this analysis is superstore.csv.

Analysis Steps
The analysis covered the following key areas:

Data Loading and Exploration:
Loading the dataset into a pandas DataFrame.
Checking for missing values and duplicate rows.
Examining data types and basic information.
Overall Performance Analysis:
Analyzing total sales by category.
Analyzing total profit by region.
Examining the correlation between numerical variables.
Identifying top-selling products and top states by sales.
Identifying bottom states and cities by profit.
Analyzing profit by sub-category.
Analyzing the impact of ship mode on sales and profit.
Time Series Analysis and Forecasting:
Preparing the sales data for time series analysis by aggregating daily sales.
Visualizing the daily sales trends over time.
Decomposing the time series into trend, seasonality, and residuals.
Training a Prophet model on the historical sales data.
Predicting future sales.
Evaluating the forecasting model.
Visualizing the historical data alongside the future predictions.
In-depth Analysis of South and Central Regions:
Filtering the data to focus on the South and Central regions.
Analyzing profit by category and sub-category within these regions.
Analyzing profit by state and city within these regions to pinpoint high-loss locations.
Examining the relationship between discount and profit in these regions.
Identifying the least profitable products in these regions.
Key Findings
The dataset is clean with no missing values or duplicate rows.
Technology is the leading category in terms of sales, while the West and East regions are the most profitable.
There is a moderate positive correlation between Sales and Profit and a weak negative correlation between Discount and Profit.
California and New York are the top states by sales, while several states and cities show significant negative profits (e.g., Texas, Ohio, Pennsylvania, Philadelphia, Houston).
'Copiers', 'Phones', and 'Accessories' are the most profitable sub-categories, while 'Tables', 'Bookcases', and 'Supplies' are among the least profitable.
'Standard Class' is the ship mode with the highest sales and profit.
The analysis of the South and Central regions revealed that 'Tables' and 'Machines' are major contributors to losses, and cities like Houston and San Antonio have substantial negative profits. Higher discounts are also associated with lower profits in these regions.
The time series analysis shows a clear trend and strong seasonality in daily sales.
The Prophet model was able to predict future sales with reasonable accuracy, providing a forecast for the next year.
Recommendations
Based on the analysis, the following recommendations are made:

Focus on Profitability in Underperforming Areas: Implement targeted strategies to address negative profits in the South and Central regions, focusing on the identified loss-driving categories, products, and locations.
Optimize Discounting: Re-evaluate the discounting strategy, especially in regions with negative profits, to ensure discounts contribute to overall profitability rather than eroding it.
Leverage Seasonal Trends: Utilize the understanding of seasonal sales patterns to optimize inventory, staffing, and marketing efforts throughout the year.
Further Investigation: Conduct deeper dives into specific areas of concern, such as the reasons for losses in particular cities or the performance of individual products within underperforming categories.
Model Improvement: Explore options to improve the accuracy of the sales forecasting model by fine-tuning parameters or considering alternative models.

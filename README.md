## Superstore Sales Dashboard
Dashboard created using Excel in order to identify the weak areas in terms of profit.
### About Dataset
*	The dataset contains information about orders placed by customers which includes sales, quantity, discount offered, profit gained, category of the product, segment in which the customer belongs to, state and region of the customer etc...
*	The data is stored in 9994 rows and 13 columns, alongwith a header row.
### Data Cleaning
*	Adjusted row height and column width.
* Converted the data range into a table called ‘tbl_superstore’.
* Removed 17 duplicates – 9977 unique values remain.
* Deleted ‘Country’ and ‘Postal Code’ columns.
* Changed ‘Discount’ to percentage.
* Added a new column called ‘Profit/Loss’ which tells whether the sales made a profit or loss or neither profit nor loss.
* Added another column called ‘City and State’ with name of the city followed by a ‘-’ and the first 3 letters of the corresponding state to distinguish cities with same name.
### EDA
*	Descriptive statistical measures such as mean, median, 1st and 3rd quartiles etc... are calulated for the numerical columns.
*	Histograms and box plots were created to understand the distribution of values in columns with numerical values.
*	Correlation between numerical columns were calculated to identify relations between the variables.
*	Scatterplots were plotted in order to clearly understand these relations, especially between profit and other variables.
### Analysis and Visualization
*	Pivot tables were created to observe trends and patterns in the total profit made with repect to each categorical variable.
*	The observed trends were visualized using pivot charts.
### Dashboard Creation
*	By using the pivot charts, a dashboard was put together to get insights on profit made and the relation between profit and discount in some areas.
*	KPIs like total sales, total profit, average discount and total quantity were added.
*	Slicers were added to give interactivity.
### Insights
*	The states with a loss are found to be offering an average discount greater than 25% whereas those with a profit offer less than 10%.
*	State with most profit is California while state with most loss is Texas.
*	States with loss have average disocunt around 40-50% for those sales which resulted in loss.
*	Copiers have made the most profit while tables have made the most loss.

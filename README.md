# Online Retail Analysis
## Tableau dashboard link [https://public.tableau.com/views/OnlineRetailAnalysisProject/Dashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link]

### Project Overview

The goal of this project is to identify trends and provide insights that will support top management in planning and implementing expansion strategies. 
This project aims to analyze various aspects of the sales data for a better understanding of the company's performance and identify opportunities for business growth.

### Data Source
Sales Data: The primary dataset used for this analysis is the "onlineretail.xlsx" containing detailed information about the customers' orders.

### Tool used
- Tableau: A powerful business intelligence tool for data cleaning, exploration, analysis, and visualization.

### Dataset Information
The "onlineretail.csv file contains" 54,9019 rows and 8 columns.
The data points are as follows;
InvoiceNO	|| StockCode || Description	|| Quantity	|| InvoiceDate	|| UnitPrice	|| CustomerID	|| Country


### Data Cleansing/Preparation

The accuracy and quality of the dataset used for the analysis is very important. To ensure the accuracy and reliability of this project, the dataset was carefully 
investigated and checked for any inconsistency and inaccuracy in the data. This is achieved by performing the following tasks:

- Loading and inspection of the dataset in Tableau
-	Relevant data points are used.
-	Datatype check: the datatype for each column was checked to ensure the right datatype is represented to prevent errors and delays in the analysis process.
-	Checked invoice date for any blank cell-No blank cell
-	The quantity column value is filtered not to be less than 1 and the unit price column is not to be less than 0. This is done to eliminate negative values in the data points.
-	Current dataset is used. The file contains 2010 and 2011 datasets, 2010 was excluded from the analysis.
-	Creation of extra column(Bin): The revenue column was created and calculated by multiplying the price and quantity
-	Null value: The customerId column contains null values. Since it will not impact the overall result of the analysis, it was not excluded.
-	The United Kingdom was excluded from the analysis using a filter as is not needed for the analysis. The country already has high market demand and the analysis is to focus on countries
  which product demand can be increased.
 	
### Exploration & Analysis

The dataset was further explored and analyzed to get the needed information by asking the following questions;
-	What is the total revenue generated in the year 2011 across months?
- The top ten countries with the highest revenue along with quantity ordered.
- The top 10 customers based on revenue generated
- The product demand across regions.
- Key performance indicators (total revenue, total quantity, number of customers)

![revenue across month 2011 (2)](https://github.com/RekkyAbdul/Online-Retail-Analysis/assets/149950425/438c4deb-e739-4add-9665-3c3fb41425e2)

![top 10 countries (2)](https://github.com/RekkyAbdul/Online-Retail-Analysis/assets/149950425/22d55f48-afe1-43ef-a83e-c981555f3eb6)

![top 10 customers (2)](https://github.com/RekkyAbdul/Online-Retail-Analysis/assets/149950425/2c4d2b70-3007-4314-bec3-d457a3261768)

![all regions (2)](https://github.com/RekkyAbdul/Online-Retail-Analysis/assets/149950425/e8070af1-4406-4308-a870-2931687262ed)





### Findings/Insights
The following insights are identified in the course of my analysis;
•	The total revenue is $9,842,938
•	Total quantity ordered is 5,229,137
•	Total customers 4,219
•	The company has the highest revenue in November, followed by October and September. The data shows that the revenue in the first 8 months is fairly constant as the average
revenue generated for these months is around $685k. The increase in revenue starts in September, when the revenue increases by 40% over the previous month. This trend continues till
November when it reaches 1.5 million USD. This shows that the sales generated during the last quarter of the year are impacted by seasonality.
•	The Top 10 countries that have growth opportunities are based on revenue generated and quantity ordered are Netherland, Eire, Germany, France, Australia, Spain, Switzerland, and Belgium. 
Sweden and Japan.
•	The map shows the region that has generated the most revenue compared to the one that has not for the business. It is seen from the map that most sales of the company come from the European 
region with very few from American region. Africa and Asia do not have any demand for the products along with Russia.
•	From the analysis based on the top ten customers, the data shows that there is not much of a difference between the purchases made by the top 10 customers. The customer with the highest revenue only 
purchases 17% more than the 2nd customer.  This shows that the business is not relying on a few customers to generate their revenue.

### Recommendations

- Implementation of effective marketing campaigns targeting November, October, and September which usually have high order rates.
- Investing more in countries such as Netherland, Eire, Germany, France, and Australia  to increase sales and profitability,
- Implementation of a new strategy targeting regions with a high potential of increasing the revenue of the business
- Effective market survey and research to identify products that will be needed by other regions yet to be part of the business source of revenue.
- Designing a loyalty program targeting top customers which will encourage them to keep patronizing the business.

### Limitations
- The total number of customers was not captured due to some null values presented in the CustomerID column. This led to an outliner in the total quantity order per customer and 
CustomerID was displayed as a null value. Therefore, it was excluded in the final visualization of the top 10 customers.
- The dataset is incomplete for December, therefore no conclusion can be drawn from it.





# Online Retail Analysis

### Project Overview

The goal of this project is to identify trends and provide insights that will support top management in planning and implementing expansion strategy. 
This project aims to analyze various aspect of the sales data for better understanding of the company performance and indentify opprtunity for business growth.

### Data Source
Sales Data: The primary dataset used for this analysis is the "onlineretail.xlsx" containing detail information about the customers' order.

### Tool used
- Tableau: A powerful business intelligent tool for the data cleaning, exploration, analysis and visualization.

### Dataset Information
The "onlineretail.csv file contains" 54,9019 rows and 8 columns.
The data points are as follows;
InvoiceNO	|| StockCode || Description	|| Quantity	|| InvoiceDate	|| UnitPrice	|| CustomerID	|| Country


### Data Cleansing/Preparation

The accuracy and quality of the dataset used for the analysis is very important. In order to ensure that the accuracy and reliability of the this project, the dataset was carefully 
investigated and checked for any inconsistency and inaccuracy in the data. This is achieved by performing the following tasks:

- Loading and inspection of dataset in Tableau
-	Relevant datapoints are used.
-	Datatype check: the datatype for each column was checked to ensure right datatype is represented to prevent errors and delay in the analysis process.
-	Checked invoice date for any blank cell-No blank cell
-	The quantity column value is filtered not to be less than 1 and the unitprice column is not be less than 0. This is done to eliminate negative values in the datapoints.
-	Current dataset is used. The file contains 2010 and 2011 dataset, 2010 was excluded from the analysis.
-	Creation of extra column(Bin): Revenue column was created and calculated by multiplying the unitprice and quantity
-	Null value: The customerId column contains null values. Since it will not impact on the overall result of the analysis, it was not excluded.
-	United Kingdom was excluded from the analysis using filter as is not needed for the analysis. The country already has high market demand and the analysis is to focus on countries
  which productdemand can be increased.
 	
### Exploration & Analysis

The dataset was further explored and analyzed to get the needed information by asking the following questions;
-	What is the total revenue generated in the year 2011 across months.
- The top ten countries with highest revenue along with quantity ordered.
- The top 10 customers base on revenue generated
- The products demand across regions.
- Key performance indicators (total revenue, total quantity, number of customers)



### Findings/Insights
The following insights are identified in the course of my analysis;
•	The total revenue is $9,842,938
•	Total quantity ordered is 5,229,137
•	Total customers 4,219
•	The company has highest revenue in the month of November, follow by October and September. The data shows that the revenue in the first 8 months is fairly constant as the average
revenue generated for these months is around $685k. The increase in revenue starts in September, where the revenue increases by 40% over the previous month. This trend continues till
month of November where it reaches 1.5 million USD. This shows that the sales generated during the last quarter of the year is impacted by seasonality.
•	The Top 10 countries which have opportunity for growth are based on revenue generated and quantity ordered are Netherland, Eire, Germany, France, Australia, Spain, Switzerland, Belgium. 
Sweden and Japan.
•	The map shows the region that has generated most revenue compared to the one that have not for the business. It is seen from the map that most sales of the company comes from European 
region with very few from American region. Africa and Asia do no have any demand for the products along with Russia.
•	From the analysis base on top ten customers, the data shows that there is no much of a difference between the purchases made by top 10 customers. The customer with highest revenue only 
purchases 17% more than the 2nd customer.  This shows that the business is not relying on few customers to generate their revenue.

### Recommendations

- Implementation of effective marketing campaigns targeting November, October and September which usually have high order rate.
- Investing more in countries such as Netherland, Eire, Germany, France and Australia  in order to increase sales and profitability,
- Implementation of new strategy targeting region with high potential of increasing the revenue of the business
- Effective market survey and research to identify products that will be needed by other regions yet to be part of the business source of revenue.
- Designing a loyalty program targeting top customers which will encourage them to keep patronizing the business.

### Limitations
- The total number of customers were not totally capture due to some null values presented in the CustomerID column. This led to an outliner in the total quantity order per customers and 
CustomerID was displayed as null value. Therefore, it was excluded in the final visualization of top 10 customers.
- The dataset is incomplete for the month of December, therefore no conclusion can be drawn from it.





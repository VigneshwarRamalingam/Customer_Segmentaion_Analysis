# Data Analytics Customer Segmentation

## Objective
This assignment aims to perform a customer segmentation analysis for a company that manufactures automobile bikes. The process of creating an RFM Model is used to segment customers. Recency, Frequency, Monetary (RFM) analysis is a behavior-based strategy that divides clients into smaller groups. Customers are grouped based on prior purchases they have made. Eleven groups comprised the client segment in this investigation. The study will assist in identifying the customer categories that should be targeted to increase sales revenue for the business. A <b>Sales Dashboard for Customer Segmentation</b> is developed using <b>Tableau</b> and the data quality assessment and analysis is done using <b>Python</b>.


## Tableau Dashboard
The Sales Dashboard for Customer Segmentation can be found [here](https://public.tableau.com/app/profile/vicky.ram/viz/Customer_segmentation_17185425519390/RFMDashboard).<br>
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/b978b80a-2d27-4bee-ac2a-d6cf74dc7cf2)

### Exploratory Data Analysis on Customer Segments
Following the data cleaning procedure, the dataset is subjected to exploratory analysis, which yields the following insights:
- <b>Age Distribution of New vs. Old Customers 
  - The majority of new clients and old customers are both between the ages of 40 and 49.
  For both sorts of clients, the age groups under 20 and over 80 had the fewest customers overall.
  - The car manufacturer is well-liked by new customers in the 40–49 and 20–29 age ranges. 
  - The 30- to 39-year-old age group shows a sharp decline in new clients.(br>
  <table>
  <tr>
    <td><b>Old Customers by Age Distribution</b></td>
    <td><b>New Customers by Age Distribution</b></td>
  </tr>
  <tr>
    <td><img src="![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/c2911f3a-afe1-4be8-9eda-2f849223f4bb)
" height="400" align="middle"></td>
    <td><img src="![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/3f698db5-da25-451e-9b24-9316cfcdcc6c)
" height="400" align="middle"></td>
  </tr>
  </table>
  
- <b>Bike purchases over last 3 years by Gender</b><br> 
   - Over the past three years, females have made the majority of bike purchases. In comparison to 49% of purchases made by men, women make about 51% of all bike purchases.
   - Purchases made by women total 10,000 more than those made by men
  ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/f86e2708-cdef-4d68-9ae6-f2cc042a004b)

  
- <b>New vs Old Customers Job Industry Distribution</b><br> 
  - Approximately 20% of new consumers come from the manufacturing and financial services sectors.
  - The telecom and agriculture sectors account for the fewest customers—roughly 3%—among the total.
  - An analogous pattern is noted among elderly clients as well.<br>
  <table>
  <tr>
    <td><b>Old Customers by Job Industry</b></td>
    <td><b>New Customers by Job Industry</b></td>
  </tr>
  <tr>
    <td>![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/23823db0-781c-4ee8-9e5e-ad31fef8c687)
</td>
    <td>![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/a89d9f9b-7d4c-493a-bdc2-bdc9f0a7b733)
</td>
  </tr>
  </table>

- <b>Wealth Segmentation by Age Category</b><br> 
  - The 'Mass Customer' Segment comprises the greatest number of customers across all age groups. The 'High Net Worth' customers make up the next category.
  - The number of clients in the Affluent sector surpasses that of the High Net Worth customers in the 40-49 age bracket.The 'Mass Customer' Segment comprises the greatest number of customers across all age groups. The 'High Net Worth' customers make up the next category.
  - The number of clients in the Affluent sector surpasses that of the High Net Worth customers in the 40-49 age bracket.<br>
  <table>
  <tr>
    <td><b>Old Customers Wealth by Age Group</b></td>
    <td><b>New Customers Wealth by Age Group</b></td>
  </tr>
  <tr>
    <td><img src="data%20visualization/Old%20Customers%20Wealth%20Segment.PNG" height="400" align="middle"></td>
    <td><img src="data%20visualization/New%20Customer%20Wealth%20Segment.PNG" height="400" align="middle"></td>
  </tr>
  </table>

- <b>Cars owned by States</b><br> 
  - New South Wales has the largest number of people who donot own a car.
  - In Victoria the proportion is quite even.
  - In Queensland the number of people owning a car is greater than who donot have a car.
  <img src="data%20visualization/Car%20Owners%20by%20State.PNG" height="400" align="middle">


### RFM Analysis and Customer Segmentation
In this stage of analysis the customer segmentation was done by developing an RFM Model. The RFM (Recency, Frequency, Monetary) analysis is a behavior-based approach grouping customers into segments. It groups the customers on the basis of their previous purchase transactions.

In this analysis the customer segment was divided into 11 groups. The groups being : 
- Platinum Customers
- Very Loyal Customers
- Recent Customers
- Potential Customers
- Lost Customers
- Losing Customers
- Late Bloomer
- High Risk Customers
- Evasive Customers
- Becoming Loyal
- Almost lost Customers

As of the current state of the Automobile business the current distribution of customers segments is depicted below:
<img src="data%20visualization/Customer%20Segment%20Distribution.PNG" height="400" align="middle">

### 4. RFM Analysis: Scatter Plots
#### Recency vs Monetary :
The visualization shows that recent customers have purchased more products and generated relatively more revenue than the customers who visited a while ageo.<br>
<img src="data%20visualization/Recency%20vs%20Monetary.PNG" height="400" align="middle"><br>

#### Frequency vs Monetary : 
The visualization shows that customers belonging to Platinum/ Very Loyal/ Becoming Loyal Customer Segments have a greater frequency and generate greater monetary for the business<br>
<img src="data%20visualization/Frequency%20vs%20Monetary.PNG" height="400" align="middle"><br>



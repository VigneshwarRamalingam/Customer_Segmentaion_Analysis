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
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/3426ccc5-cf48-4e4f-850f-851f62c94a49) ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/7b64695e-40e9-4b1d-b886-516dd1710db5)


  
- <b>Bike purchases over last 3 years by Gender</b><br> 
   - Over the past three years, females have made the majority of bike purchases. In comparison to 49% of purchases made by men, women make about 51% of all bike purchases.
   - Purchases made by women total 10,000 more than those made by men
  ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/f86e2708-cdef-4d68-9ae6-f2cc042a004b)

  
- <b>New vs Old Customers Job Industry Distribution</b><br> 
  - Approximately 20% of new consumers come from the manufacturing and financial services sectors.
  - The telecom and agriculture sectors account for the fewest customers—roughly 3%—among the total.
  - An analogous pattern is noted among elderly clients as well.<br>
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/b9111295-4bd9-445a-a817-9f6248a5e194) ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/4dc023f9-b4e6-4a63-9028-008fd2b7c5c3)



- <b>Wealth Segmentation by Age Category</b><br> 
  - The 'Mass Customer' Segment comprises the greatest number of customers across all age groups. The 'High Net Worth' customers make up the next category.
  - The number of clients in the Affluent sector surpasses that of the High Net Worth customers in the 40-49 age bracket.The 'Mass Customer' Segment comprises the greatest number of customers across all age groups. The 'High Net Worth' customers make up the next category.
  - The number of clients in the Affluent sector surpasses that of the High Net Worth customers in the 40-49 age bracket.<br>
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/eafac973-6c25-4aca-a2f7-ef59d0cf832e) ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/b9c142d4-2939-459f-add9-6fcffcadd32f)



- <b>Cars owned by States</b><br> 
  - New South Wales has the largest number of people who donot own a car.
  - In Victoria the proportion is quite even.
  - In Queensland the number of people owning a car is greater than who donot have a car.
 ![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/2fc6729c-d247-45fa-8576-7d3602167a8c)




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
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/1d7dccd9-ed59-4351-a7aa-d7b5caa0b3f1)


### 4. RFM Analysis: Scatter Plots
#### Recency vs Monetary :
The visualization shows that recent customers have purchased more products and generated relatively more revenue than the customers who visited a while ageo.<br>
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/238c7d99-4216-4764-85b4-13f7a08a212c)
<br>

#### Frequency vs Monetary : 
The visualization shows that customers belonging to Platinum/ Very Loyal/ Becoming Loyal Customer Segments have a greater frequency and generate greater monetary for the business<br>
![image](https://github.com/VigneshwarRamalingam/Customer_Segmentaion_Analysis/assets/104707588/5cdd0c0e-428d-4d2f-83eb-56fcce141d0a)
<br>



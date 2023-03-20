Technical case study
Guidelines
1.	Understanding of Data- How well do you understand the problem statement and the data. You can optionally, demonstrate it using data visualization which will also help us to understand your solution better
2.	Code Quality- We expect you to write a clean code as if you were writing this in production
3.	More than the final result we want to understand your approach towards solving an end to end business problem using machine learning techniques
4.	Call out any assumptions you have taken during the analysis

Problem Statement
ABC Inc is a US based specialty retailer of crafts and fabrics. ABC Inc wants to predict the sales of their products based on historic sales. They already have a forecasting system in place, but its accuracy is low.  Sales forecast will feed into the budget planning and hence needs to have good accuracy. As an analytics consultant, ABC Inc have approached you to build a forecasting system with good accuracy.	
The retailer runs promotions at different parts of the year with an expectation to increase the margin. Given the daily sales data for 2017, 2018 and 2019 at Product level and the Promotion Calendar, you need to predict the sales of the products for the time-period: 1st Jan’2020 to 31st March’2020
Datasets
1.	Sales Data – Sales data at day level with promotions on each day
2.	Promotion Calendar – Promotion calendar for the future period
3.	Product Master – Product hierarchy along with the Unit Retail Price of the product
Data Dictionary
1.	Sales Data
a.	Product : Product of interest
b.	Date : Date on which the transaction is done
c.	Offer : Offer amount
d.	Offer Type : Type of the promotion 
e.	Quantity – Quantity sold for each day for each product
Note for offer type : There are 3 types of offers, which are given as P, F, and A.
•	P (Percentage offer) : x% offer on the Unit Retail Price (Unit Retail Price is same as MRP)
•	F (Fixed offer) : Buy a product for $9.99. Regardless of the URP of the product, customer will get it for $9.99. For instance, if URP is $24.99, amount customer has to pay after promotion will be $9.99
•	A (Amount offer) : Buy a product for $9.99 off. This means that customer will get a discount of $9.99 on the URP. For instance, if URP is $24.99, amount customer has to pay after promotion will be $15

2.	Promotion Calendar
a.	Product : Product of interest
b.	Promotion Start : Start date of promotion
c.	Promotion End : End date of promtion
d.	Offer : Offer amount
e.	Offer Type : Type of promotion

3.	Product master
a.	Product : Product of interest
b.	Sub Category : Product hierarchy 1
c.	Category : Product hierarchy 2
d.	Unit Retail Price : Price of the product

Questions for Business / Data Understanding:
1.	Detect the outliers in the quantity and apply an outlier treatment on the same. Specify the outlier treatment technique and reason for choosing the same
2.	Check the data for missing values and apply the missing value treatment. Also provide the reasoning for the missing value treatment method used
3.	Check for seasonality and trend effect and smoothen if needed
4.	Results of EDA performed, if any
5.	Fit a model to predict the quantity from 1st Jan 2020 to 31st Mar 2020
6.	Evaluate your model performance

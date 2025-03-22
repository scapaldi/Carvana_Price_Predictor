# Carvana_Price_Predictor
Machine Learning - Can Carvana data be used to predict price of an automobile

Introduction:
Carvana Co. is an online automobile retailer based in Tempe, Arizona that performs almost all the functions a physical dealer would offer: buying and selling cars, accepting trade-ins, and financing purchases.  It's as easy as going to the Carvana home page and clicking "Search Cars."  Vehicles costing from around $7000 to $100,000 are sourced from auctions and dealer partners, trade-ins, and private sellers.  Carvana also offers financing through the company as well as a 7-day money back guarantee if you don't like your car. 

Overview of Project:
It’s believed that a car’s value decreases with age (Year) and Mileage.  If this is true then buyers have the advantage when shopping for used cars as they can use Year and Mileage or both as an indicator for offering a lower price for a particular car.  It’s true that some car makes have higher prices vs. others (say BWM are more expensive than a Chevy) but, if the above is true, then a used BWM will still have less value than a used BWM.  The meaning is that Miles and Year can be used to asses car’s value regardless of Make and Model.

Problem Statement: How can we predict car prices for Carvana's inventory based on both mileage and age to help ensure customers are not overpaying for a vehicle.

Project Description:
This project is aimed at helping customers understand that car prices decrease in relation to a car's age and increased mileage.  It's true, some cars increase in price with age, but these cars are considered a "classic": a delegation by the DMV if a car is over 20 years old.  A car can only increase in value with age if it's A) rare and B) in demand by a collector, but these two variables our outside the scope of this test as a car's age in this dataset is between 2009 and 2023.
We will focus on two main correlations: (1) that a customer can observe a car's value decreases with age and (2) that the car's value decreases with mileage.  I feel these two branches of the project will combine to give the customer a better understanding of a car's value in relation to these two variables individually and combined to help customers find purchase options within their budget.

Solution:
The goal of this project is to provide a graph and chart where users can base the price of a vehicle based upon a car’s age and mileage.
Planned model is to use linear regression to identify a correlation between a car’s price and age.  This method is considered a supervised learning algorithm as it requires labeled data to train and predict continuous values based on the relationship between independent and dependent variables.  This dataset will be used to train future datasets as Carvana's inventory increases with the purchase of new vehicles.
The desired results should show a linear, downward sloping graph showing a car’s value decreases as mileage and age increase.

Output data will show:
(1) a heatmap displaying highest correlation values:
 
(2) correlation graph for individual values (year, mileage) compared to year:
 
(3) plot of the residual data:
 
Data Analytics:
I’ll be using correlation test to see if a correlation exists.  Regardless of the p-value, the results will be graphed using a scatter plot.
Machine Learning:
Machine model used will be linear regression analysis as it's used to predict the value of a variable based on the value of another variable.  The variable you want to predict will be a car's price.  Also, can a car's year and mileage be used to predict its value for all new cars purchased by Carvana?

Summary:
Carvana Co. would like to create a machine model to accurately predict the price of incoming cars based upon Year and Mileage.  Common sense tells buyers that a car’s value decreases with both age and mileage.  Our findings based upon this test show there is no correlation between a car’s price, year and mileage.
Our conclusion shows that predicting a car’s value can not, at this time, be automated based upon these variables.

Dataset:
•	Link for  dataset: https://www.kaggle.com/datasets/ravishah1/carvana-predict-car-prices


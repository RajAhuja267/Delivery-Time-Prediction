# Delivery-Time-Prediction
Problem Statement:
This data is from thousands of restaurants in India regarding the time they take to deliver food for online order. Our goal is to predict the online order delivery time based on the given factors.
Size of training set: 11,094 records
Size of test set: 2,774 records

Features:
•	Restaurant: A unique ID that represents a restaurant.
•	Location: The location of the restaurant.
•	Cuisines: The cuisines offered by the restaurant.
•	Average_Cost: The average cost for one person/order.
•	Minimum_Order: The minimum order amount.
•	Rating: Customer rating for the restaurant.
•	Votes: The total number of customer votes for the restaurant.
•	Reviews: The number of customer reviews for the restaurant.
•	Delivery_Time: The order delivery time of the restaurant. (Target Classes) 

Steps:
1)	We will import the required libraries and Load the Training and Testing data.
2)	Then we will remove the rupee symbol to ease the calculations,
3)	Then we will extract city from the given Location variable and save the City wise data.
4)	 Then we will convert object data type to numeric data type of all variables.
5)	Then we will check the missing values here there are no missing values.
6)	After that we will do Exploratory Data Analysis of the data.
7)	After that we will scale the data and then apply different algorithms like Decision Tree Classifier, Random Forest Classifier, Support Vector Machine and K-Nearest Neighbourhood.

Conclusion: 
From the results we can conclude that Random Forest Algorithm gives the best accuracy of (78%) with Average Delivery Time of (30 minutes).

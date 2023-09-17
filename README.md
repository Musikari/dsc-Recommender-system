# A NON-STORE ONLINE BUSINESS RECOMMENDER SYSTEM

![Alt text](<Images/Image4.png>)
Images/Image4.png

## INTRODUCTION

A non-store online retail business represents an e-commerce venture that conducts all its business in the digital realm and doesn't have a physical location. This service is offered by companies through websites and applications where customers place orders via the Internet, and products are shipped directly to their addresses. These businesses have grown significantly in popularity, particularly since the COVID-19 pandemic. Lockdowns and social distancing measures forced consumers to look for safer and more practical ways to shop, and non-store online retailers were crucial during this time as they were able to provide a wide array of products and services accessible from the safety of one's home.
An advantage to online non-store retail business there is a wide selection of goods, buyer and shopping secrecy exists, customers can avoid long lines, unique and rare goods can be found, and there is comprehensive information about the goods that you are purchasing as well as online discounts. In order to effect the benefits of online shopping, one can employ a recommendation system that serves as an information filtering tool, working to anticipate a user's preferences and offer recommendations tailored to those preferences.


## PROBLEM STATEMENT

Problem Statement
Non-store online retail business faces several challenges and issues that require attention in order to succeed in the digital marketplace. various challenges such as customer engagement, product discovery, personalization, and inventory management. These processes can be tedious as they have to collect information on customer preferences, cost of items, quality of products, and durability among other factors. In most cases, these retailers are not able to get this information and therefore this can have a negative impact on their businesses. A UK-based online retail company that specializes in selling unique all-occasion gifts, catering to both individual customers and wholesalers who are the stakeholders understands the importance of a recommendation system that will help them address these challenges and enhance the customer experience.

From the several factors, our primary objective that we aim to achieve are:

* enhancing customer engagement by offering personalized product recommendations based on user preferences and purchase history.
* Mitigate the product discovery challenge by highlighting relevant items, making the shopping experience more enjoyable and efficient.
 

## DATA UNDERSTANDING

We will make use of the data set from the UCI MachineLearning Repository. It is a transnational data set which contains transaction between the year 2010 and 2011 for a UK-based and registered non-store online shop selling unique gifts
 
Description of Columns:  
The data set has the following 8 columns which are:

* `InvoiceNo` - Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* `StockCode` - Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* `Description`  Product (item) name. Nominal.
* `Quantity` - The quantities of each product (item) per transaction. Numeric.
* `InvoiceDate` - Invoice Date and time. Numeric, the day and time when each transaction was generated.
* `UnitPrice` - Unit price. Numeric, Product price per unit in sterling.
* `CustomerID` - Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* `Country` -Country name. Nominal, the name of the country where each customer resides.
# DATA CLEANING

Performed the following data-cleaning processes:
* Imported the data.

* Changed the date type.

* Dropping duplicate values.

* Removed outliers in the Unit price and Quantity column.

* Dropped all the null values in the column.



# EXPLORATORY DATA ANALYSIS

* Univariate Analysis

![Alt text](<Images/Image2.png>)


* Bivariate Analysis

![Alt text](<Images/Image3.png>)

* Multivariate Analysis

![Alt text](<Images/Image1.png>)



## Modeling
We used the following regression models:

* Memory_Based Model using Cosine and Pearson Similarity
* Collaborative Filtering - Using Surprise Library

* Evalustion RMSE

## Conclusion

* The best time to offer discounts to customers was the month of November which had the highest number of sales. 
    
* The appropriate time for ads on is in the afternoon which is the peak hours of the day that most people purchase goods.

* The quantity of orders made are not affected with the price of an item as there is no relation betwen the quantity and price.

* Thursday and sundays are the days of the week with the highest quantity interms of purchase made.

* KNN (K-Nearest Neighbours) With Means model has an test RMSE value of 0.244 and cross validation RMSE value of 0.246.


* White hanging  light holder has the highest number of orders where as the pack of 72 retrosport cake has the least number of orders.


## Recommendation
* The recommendation system developed will be very helpful to the customers and e-commerce companies to offer personalized product recommendation based on user preference and purchase history.
  
* One is also able to mitigate the product discovery challenge by highlighting relevant items, making the shopping experience more enjoyable and efficient. However we can improve this recommendation engine using Deep Learning Techniques and Deep Hybrid Models Based Recommendation, many neural building blocks can be integrated to formalize more powerful and expressive models."
  
## Non-Technical Presentation

To access the non-technical presentation click here [Link](https://docs.google.com/presentation/d/1TOd9Cb0dX8W5OLbUASLv89wSEjf93IByFdxn-rfN59U/edit?usp=sharing)

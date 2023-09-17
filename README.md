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

![Alt text](<Images/Image1.png>)


* Bivariate Analysis

![Alt text](<Images/Image3.png>)

* Multivariate Analysis

![Alt text](<Images/Image1.png>)


# MODELING

#### Research Question:
What are the significant factors influencing the severity of traffic crashes, and can they be used to predict the severity level (e.g., minor, moderate, severe)?

Prediction and Evaluation: We Predict outcomes on the test set and evaluate the model's performance using a confusion matrix and classification report.

The model achieved an accuracy of approximately 90%. The classification report provides a detailed breakdown of performance for each class, including precision, recall, and F1-score. The weighted average F1-score gives an overall measure of the model's performance across all classes.

Overall, the model appears to perform well, particularly in identifying "INCAPACITATING INJURY" cases. However, it shows lower recall for the "REPORTED, NOT EVIDENT" class, indicating potential room for improvement in identifying such cases. 

#### Research Question:
Effectiveness of Safety Equipment:

Research Question: What is the impact of safety equipment usage (e.g., seatbelts, airbags) on the occurrence and outcomes of crashes, and can we quantify their effectiveness in reducing injuries?

![Alt text](images/image-2.png)

The model had the following scores:
RMSE: 0.33
Recall: 0.9
Precision: 0.88
Accuracy: 0.89
F1-Score: 0.89

#### Research Question:

Geographic Hotspots and Prevention Strategies:<br>
Research Question: Can we identify geographic hotspots with higher crash frequencies, and what targeted prevention strategies (e.g., improved signage, traffic control) can be recommended

![Alt text](images/image-4.png)

The model had the following scores:
RMSE: 0.58
Recall: 0.61
Precision: 0.72
Accuracy: 0.67
F1-Score: 0.66

# Conclusions

1. The predictive model demonstrated a high accuracy rate in determining accident severity, particularly for cases involving incapacitating injuries. There is room for further improvement, especially in identifying cases with reported but not evident injuries.

2. Geographic analysis revealed areas with higher crash frequencies, suggesting targeted interventions like enhanced traffic enforcement and infrastructure improvements. The model predicted that areas without traffic control devices recorded injuries as compared to areas with traffic control devices. 

3. Road safety In Chicago Pd is an ongoing concern that requires continuous monitoring and improvement of strategies based on the data and changing circumstances.

# Recommendations

Drawing upon the observations and instances mentioned above, we have the opportunity to formulate the subsequent set of recommendations:

 1. Regular Monitoring and Timely Maintenance of Road Surface Conditions:
        It is strongly advised to establish a systematic and vigilant approach to consistently monitor and proactively maintain the condition of road surfaces. Swiftly addressing issues such as potholes, cracks, and uneven surfaces is of paramount importance to ensure the safety and comfort of motorists and pedestrians. 
 2. Fostering Collaboration with the Automotive Industry for Enhanced Vehicle Stability:
        To synergize advancements in road safety and automotive technology, a collaborative partnership between the transportation sector and the automotive industry is highly recommended. By jointly developing cutting-edge technologies that enhance vehicle stability, such as adaptive suspension systems and advanced driver assistance features, the collective efforts can yield remarkable improvements in overall road safety.
 3. Developing Weather-Responsive and Adaptive Road Infrastructure:
       In order to effectively mitigate the impact of changing weather conditions on road safety and durability, it is recommended to embark on the development of road infrastructure that demonstrates a high degree of responsiveness to varying climatic factors.         

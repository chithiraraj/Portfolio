Part - A
 

Business Context:
An automobile parts manufacturing company has been actively selling products to a diverse range of customers for the past three years. Despite its growth, the company lacks the in-house expertise to derive actionable insights from its transaction data. As a result, they wish to uncover hidden patterns and trends in their customer transactions. By analyzing this data, the company aims to better understand customer behavior, improve customer segmentation, and implement targeted marketing strategies. These insights will help the company not only enhance customer satisfaction but also drive revenue growth by offering more personalized and efficient services.

 

Objective:
The primary objective of this analysis is to leverage data science techniques to:

Identify underlying patterns in customer purchasing behavior.
Segment customers based on their transactional data.
Provide actionable insights to optimize the company's marketing efforts.
Recommend personalized marketing strategies for each customer segment to maximize sales and customer retention.
Your role as a Business Analyst is to use the provided dataset to achieve these goals and present findings in a manner that can guide the company's decision-making.

 

Data Description:
The dataset provided contains three years of transactional data from the company, with each row representing a unique order. Below is an explanation of the key attributes:

ORDERNUMBER: Unique identifier for each order.
QUANTITYORDERED: Number of items ordered in a specific transaction.
PRICEEACH: Price per unit of the product in the order.
ORDERLINENUMBER: Sequence number of the product in the order.
SALES: Total sales value for the order.
ORDERDATE: Date when the order was placed.
DAYS_SINCE_LASTORDER: Number of days since the customer's previous order.
STATUS: Current status of the order (e.g., Shipped, Disputed).
PRODUCTLINE: Product category to which the item belongs (e.g., Motorcycles, Classic Cars).
MSRP: Manufacturer’s Suggested Retail Price for the product.
PRODUCTCODE: Unique identifier for the product.
CUSTOMERNAME: Name of the customer placing the order.
PHONE: Customer's contact phone number.
ADDRESSLINE1: Customer's primary address.
CITY: City of the customer's address.
POSTALCODE: Postal code of the customer's address.
COUNTRY: Country of the customer's address.
CONTACTLASTNAME: Last name of the customer’s contact person.
CONTACTFIRSTNAME: First name of the customer’s contact person.
DEALSIZE: Size category of the transaction (e.g., Small, Medium, Large).
 

 

Part - B
 

Business Context:
In the highly competitive grocery retail industry, understanding customer buying patterns is crucial for enhancing sales, increasing customer satisfaction, and improving profitability. By identifying frequently purchased item combinations, grocery stores can craft effective marketing strategies, optimize inventory management, and tailor promotions to meet customer needs. Leveraging Point of Sale (POS) data can unlock valuable insights that drive customer-centric offerings, such as combo packs, discounts, and targeted promotions, which can increase basket size and improve customer retention. This analysis aligns with business goals by maximizing revenue, reducing operational costs, and boosting customer loyalty.

 

Objective:
As a business analyst, the goal is to analyze the POS transactional data to identify frequently purchased item combinations. Using association rule mining or similar techniques, the aim is to uncover patterns that will help the store create targeted combo offers and discounts, ultimately driving revenue growth by increasing customer purchases and average basket size.

 

Data Description:
The dataset consists of transactional data from a grocery store, where each row represents a product purchased in a specific order. The columns in the dataset are as follows:

Date: The date when the transaction took place.
Order_id: A unique identifier for each customer order.
Product: The individual item purchased in the transaction.

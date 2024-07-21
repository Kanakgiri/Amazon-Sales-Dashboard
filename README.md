# Amazon Sales Dashboard

## Purpose Of The Project

The project aims to analyze sales, optimize logistics, track seller performance, assess discount impacts, and measure customer satisfaction using data like order details, product categories, shipment status, and sales metrics to inform business strategies and improve operational efficiency.


![Overview](https://github.com/Kanakgiri/Amazon-Sales-Dashboard/assets/171118310/0988564e-0e26-45a6-9b30-21ac3054de25)
![Products](https://github.com/Kanakgiri/Amazon-Sales-Dashboard/assets/171118310/7be3e16c-0b26-40d0-bd91-7a278f6b557c)


## About Data

The data includes information like Order-ID, Date, Status of the shipment, Category of the product, Size, Quantity, Ship-city, Ship-state, Postalcode, Colour, Image-Url, Discount, Sale-Price and Seller-ID.
There are two data-sets (Amazon Sale Report and Amazon Fashion) which contain 128,977 rows, 19 columns and 29,925 rows, 19 columns respectively.

## Tools Used

- Microsoft Excel
- Power BI

## Approach Used

- Feature Engineering: This will help us generate some new columns from existing ones using Power Query.

The column `Large` is transformed to store only one Url of product image which previously contained two or more Urls.

The column `Category` is transformed to have space between the words and null values are replaced by Blanks so that they can be added to Slicers.

New measures were created in Power BI to calculate total number of units sold, price of each unit and Total Amount.

- Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

## Conclusion:

Business Questions Answered

1. What is the total number of sellers and total number of units sold?
- The total number of sellers is 2404 and total number of units sold is 120,528.

2. What are the total sales made by all the sellers?
- The total sale during the three months period (April-June) is ₹ 98.43 million.

3. How do sales vary by week of the months?
- Sales remain almost consistant on all weeks but on first week of May there is a slight increase in sales followed by sharp decline.

4. Which are the top performing States in terms of Sales?
- Maharashtra was the top performing state followed by Karnataka, Tamilnadu, Telangana and Uttar Pradesh.

4. Which are the top performing Cities in terms of Sales?
- Bengaluru was the top performing City followed by Hyderabad, Mumbai, New Delhi and Chennai.

5. What is the average price/order per Sale?
- Average price/order per Sale is ₹ 820.

6. How many orders were cancelled?
- A total of 6368 orders were cancelled from 1622 sellers. The total sale amount was 13.93 million.

7. How many orders were Shipped?
- A total of 80,263 orders were Shipped from 2372 sellers. The total sale amount was 59.42 million.

8. How many orders were Delivered to Buyer?
- A total of 30,319 orders were Delivered to Buyer from 1921 sellers. The total sale amount was 22 million.



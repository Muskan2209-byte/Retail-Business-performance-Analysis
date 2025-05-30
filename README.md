# Retail-Business-performance-Analysis:
This project demonstrates an analysis of a superstore's sales data, utilizing Power Query for data transformation, DAX for advanced calculations, and Data Modeling for structuring relationships between tables. The final visualizations are presented through interactive dashboards in Power BI.

# Case Study:
A superstore retail business is a large, multi-department store that sells various products, including groceries, electronics, home goods, clothing, and more. These stores are often designed to be a one-stop shop for customers, offering a wide range of products and services under one roof. Superstores are typically larger than traditional retail stores and may have a larger product selection. Superstores are often part of a larger chain and have multiple locations in a region or country.

# Data Set Description:
A Superstore dataset includes information about the products, customers, and sales associated with a retail store. It may include the following columns:

Sl.No	Column Name	Column Description
1	Order ID	Unique Identifier For the Order
2	Order Date	Date of the order placed
3	Ship Date	Date of the order shipped
4	Ship Mode	Priority Mode of Shipping (Same Day, First Class, Second Class, Standard Class)
5	Customer ID	Customer Unique Identifier
6	Customer Name	Name of the customer
7	Segment	Customer Segment (Consumer, Corporate, Home Office)
8	Postal Code	Address from the order was placed
9	Region	Name of the Region
10	Product ID	Unique Product Identifier
11	Category	Product Category
12	Sub-Category	Product Sub - Category
13	Product Name	Name of the Product
14	Quantity	Quantity of the product ordered
15	Discount	Discount % on the product
16	Buy Price	Buying price for each item
17	Price	Per Each Selling price for each item

# Tools Used:
a. Power Query : For data cleaning, transformation, and preparation.

b. Data Modeling : Creating relationships between various tables like orders, products, customers, and regions.

c. DAX (Data Analysis Expressions) : For custom measures, calculations, and KPIs to perform dynamic analysis.

d. Power BI Visualizations : For creating interactive and visually appealing reports to deliver business insights.

# Key Insights:
* Sales and Growth :-
  
  1- Total Sales : ₹ 2.33 million, with ₹ 923.13K coming from discounted sales.

  2- Yearly Sales : Sales steadily increased from ₹ 470,636 in 2014 to ₹ 750,471 in 2017.

  3- The overall growth rate from 2014 to 2017 is 47.45%.

  4- Year-over-Year (YoY) Growth : YoY growth has been positive except in 2017, which saw a 19.65% increase in sales compared to 2016. The largest YoY growth 
    occurred between 2015 and 2016 at 29.68%.

  5- Month-over-Month (MoM) Sales : The dashboard shows fluctuating MoM sales, with extreme swings such as a 684.77% increase in March 2014, followed by 
    significant drops. This indicates that sales are highly seasonal and likely driven by promotions or other factors.

* Geographic Insights :-
  
  1- Sales by Region :
  West : ₹ 742,919 (highest)
  East : ₹ 695,776
  Central: ₹ 499,995
  South : ₹ 393,324
  
  2- California is the top-performing state with ₹ 471,811 in sales, followed by New York at ₹ 357,898.
  
* Product and Segment Insights :-
  
  1- Sales by Category :

  Technology : Top category, generating the highest sales at ₹ 872,745.
  Office Supplies : ₹ 798,889
  Furniture : ₹ 660,381
  
  2- Sub-categories like copiers and appliances also play a significant role in total sales.

* Order Size :-
  The largest portion of sales came from low cart sizes with over 50% discounts. This suggests customers are attracted to discounted items in smaller quantities.

* Profitability Insights :-
  
  1- Profit by Category :

  Office supplies and technology are the most profitable categories, while furniture shows negative profits.
  
  2- Total profit is ₹ 34,822, with the West region contributing the most at ₹ 17,469.

  3- Copiers and Accessories are the top sub-categories in terms of profitability, with copiers generating over ₹ 33K in profit.

* Operational Insights :-
  
  1- Delivery Times :

  Standard Class : 5 days (longest average delivery time).
  Same Day : Less than 1 day (quickest).
  
  2- Order Patterns : Orders are highest on Monday and Friday, but drop significantly on weekends.

# Key Takeaways:

1- Sales growth is driven by discounted products, especially in office supplies and technology.

2- Geographic regions like the West and East dominate sales, with California being a critical market.

3- Profit margins are higher in technology and office supplies, but profitability in furniture is concerning with a negative contribution.

4- Delivery times and order patterns suggest opportunities for improving operational efficiency, particularly in reducing delivery times for standard shipping.

# Recommendations:

1-Leverage Discounted Sales :
  Since a significant portion of sales comes from discounted products, especially small cart sizes, it may be beneficial to continue offering strategic 
  discounts, particularly for office supplies and technology, which perform well in this regard.

2-Focus on High-Performing Regions :
  The West and East regions, especially California, are your strongest markets. Consider focusing marketing and promotions in these regions to maximize growth 
  potential.

3-Improve Profitability in Furniture :
  Furniture shows negative profitability. It may be wise to assess costs, pricing strategies, or product demand within this category to turn it around.

4-Optimize Shipping Times :
  Standard Class shipments have the longest delivery time (5 days). Streamlining this process or offering incentives for faster shipping options could improve 
  customer satisfaction and boost sales.

5-Target Order Peaks :
  Since orders peak on Mondays and Fridays, you can consider running promotions or marketing campaigns aligned with these days to capitalize on customer buying 
  behavior.

6-Seasonal and Promotional Planning :
  With high fluctuations in Month-over-Month sales, planning for key seasonal promotions or events where sales spike (like March and November) could help smoothen 
  sales volatility.

OBJECTIVE: Utilize clustering algorithms to segment customers based on their spending behavior and demographic information. Provide actionable insights to marketing teams for targeted campaign strategies.

SUBJECT DETAILS: 
- Customer Personality Analysis is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors and concerns of different types of customers.
- Customer personality analysis helps a business to modify its product based on its target customers from different types of customer segments. For example, instead of spending money to market a new product to every customer in the company’s database, a company can analyze which customer segment is most likely to buy the product and then market the product only on that particular segment.

PROCEDURE SUMMARY:
- In this project, I have performed an unsupervised clustering of data on the customer's records from a groceries firm's database.
- Customer segmentation is the practice of separating customers into groups that reflect similarities among customers in each cluster.
- I will divide customers into segments to optimize the significance of each customer to the business. To modify products according to distinct needs and behaviours of the customers.

DATASET ATTRIBUTES:

- People
ID: Customer's unique identifier
| Year_Birth: Customer's birth year
| Education: Customer's education level
| Marital_Status: Customer's marital status
| Income: Customer's yearly household income
| Kidhome: Number of children in customer's household
| Teenhome: Number of teenagers in customer's household
| Dt_Customer: Date of customer's enrollment with the company
| Recency: Number of days since customer's last purchase
| Complain: 1 if the customer complained in the last 2 years, 0 otherwise

- Products
| MntWines: Amount spent on wine in last 2 years
| MntFruits: Amount spent on fruits in last 2 years
| MntMeatProducts: Amount spent on meat in last 2 years
| MntFishProducts: Amount spent on fish in last 2 years
| MntSweetProducts: Amount spent on sweets in last 2 years
| MntGoldProds: Amount spent on gold in last 2 years

- Promotion
| NumDealsPurchases: Number of purchases made with a discount
| AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
| AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
| AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
| AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
| AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
| Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

- Place
NumWebPurchases: Number of purchases made through the company’s website
NumCatalogPurchases: Number of purchases made using a catalogue
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company’s website in the last month


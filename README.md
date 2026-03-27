**Customer Order Processing and Analysis Using Python**

In this project, I worked with customer order data using Python. The main aim of this task was to understand how Python data structures like lists, tuples, dictionaries, and sets can be used to store and analyze data. By
using these structures, I was able to organize customer orders, calculate how much each customer spent, and generate some useful insights from the data.

**Storing Customer Orders :**
First, I created a list of customer names. After that, I stored customer order details using tuples. Each tuple contains the customer name, the product they purchased, the price of the product, and the category it belongs
to. All these tuples were stored inside a list called order_details. I also created a dictionary where the key is the customer name and the value is the list of products they ordered. This made it easier to access and update customer records when needed.

**Classifying Products by Category:**
Next, I created a dictionary that maps each product to its category, such as Electronics, Clothing, or Home. Using this dictionary, I created a set to get all the unique product categories. Since sets automatically remove
duplicates, it helped in getting a clean list of available categories. Finally, I displayed all the product categories to see what types of products are available in the data.

**Analyzing Customer Orders:**
To analyze the orders, I used a loop to calculate the total amount each customer spent. Every time a customer appeared in the order list, their purchase amount was added to their total. Based on the total spending, customers were classified into three groups: 
- High-value buyers if their spending was more than $100
- Moderate buyers if their spending was between $50 and $100
- Low-value buyers if their spending was below $50
This helped in identifying which customers contribute more to the business.

**Generating Business Insights:**
After calculating the customer spending, I generated some insights from the data. I calculated the total revenue for each product category and stored it in a dictionary. I also extracted unique products from all the orders using a set. Then I used a list comprehension to find customers who purchased electronics products.To find the top customers, I sorted the customer spending data and selected the top three highest-spending customers.

**Organizing and Displaying Results:**
Finally, I printed a summary showing each customer's total spending along with their classification (high-value, moderate, or low-value buyer). I also used set operations to find customers who purchased products from multiple categories. Additionally, I identified customers who bought products from both electronics and clothing categories.

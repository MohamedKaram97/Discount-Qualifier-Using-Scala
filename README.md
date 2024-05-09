# Discount-Qualifier-Using-Scala
A huge retail store wants a rule engine that qualifies orders’ transactions to discounts based on a set of qualifying rules. And automatically calculates the proper discount based on some calculation rules

# Business Requirements
As mentioned above, the retail store has many orders to specify whether they need a discount or not, then add discount to them according to a specific criteria. This criteria has some qualifying rules and each qualifying rule has a corresponding calculation rule to be applied on the orders that meet this qualifying rule. It's a hard process to be performed manually, so a Discount Engine is used to ease this process and make changing the criteria at any time a more flexible action.

Let's dig deeper into the discount engine's qualifying rules and their corresponding calculation rules:

# Extra Rules:

Transactions that didn't qualify to any discount will have 0% discount
Transactions that qualified to more than one discount will get the average of the top 2 discounts
Extra qualifying and calculation rules may be added at any time
Business also needs to store the processed information into any database, I chose Oracle DBMS.

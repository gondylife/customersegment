# customersegment
A machine learning model for customer segment clustering.

# Project Context
My client is an online retailer based in the UK. They sell all-occasion gifts, and many of their customers are wholesalers.

* Most of their customers are from the UK, but they have a small percent of customers from other countries.
* They want to create groups of these international customers based on their previous purchase patterns.
* Their goal is to provide more tailored services and improve the way they market to these international customers.

# Current Solution
Currently, the retailer simply groups their international customers by country. As you'll see in the project, this is quite inefficient because:

* There's a large number of countries (which kinda defeats the purpose of creating groups).
* Some countries have very few customers.
* This approach treats large and small customers the same, regardless of their purchase patterns.

# My Role
The retailer has hired me to help them create customer clusters, a.k.a "customer segments," through a data-driven approach.

* They've provided me a dataset of past purchase data at the transaction level (you'll see why this will be important).
* My task is to build a clustering model using that dataset.
* My clustering model should factor in both aggregate sales patterns and specific items purchased.

# DBMS

A small trading company has approached you for database design to support their business. In a conference room pilot (CPR), you have listened to their top five questions that the operations manager mentioned which must be demonstrated with sample data. The staff of operations explained the business as follows so that you could design the database for them, populate it with sample data and answer the operations manager’s questions. You have made a note of all communication as follows:
Operations Staff: Customers come to our trading center, call us or email us with one or more products that we sell. We have a variety of products to sell ranging from stationery items to computers and other accessories. Since we don’t stock products and work with just-in-time inventory, we try to ship the order in the following week. Therefore, we take orders and keep order invoice for our records. Our trading center is not open during weekends. Our operations manager consolidates all orders from the same customer and assigns a new sales invoice number on Friday after we close the trading center for our customers.  As far as the customer is concerned the order date id the date on which we invoiced the customer, as we allow up to 30 days of credit without any interest, after which we charge 3% on any portion of remaining balance once in 30 days and raise the required voucher separately for the customer rather than adding it to the invoice amount until the invoice is paid in full. Once the invoice is paid completely, we follow up with the customer for the balance on vouchers separately. The customers may make partial payments and they usually do not mention any invoice number, but send us the payment by check or wire transfer. We apply the payment to the oldest sales invoice. In doing some if the same product was ordered on two different days during the week before consolidation, we apply the payment to the oldest order invoice first. We also have a standard practice of applying the balance to the order line of least value in the oldest order invoice. So to say, we have a tally at the order line level rather than the order level. We allow customers who  want to cancel or change any order or portion of it before the orders get consolidated, as it will affect our just-in-time purchase orders placement which is done every Monday. What we make sure is that when a customer has any pending balance because of accrued interest, we apply for any payment by the customer to that first before considering any order invoices.

Operations Manager: I want only order, sales, customer, voucher maintenance to be in the database and purchase side of the business, we will take it up in the next iteration after you have successfully demonstrated the top five questions I have:

How do I automate the order consolidation and sales invoice generation which I have been doing manually?
What are the five customers performing well by paying all invoices within 30 days?
What are the five customers performing poorly by not paying all of the invoices within 30 days?
What are the customers  performing well by clearing the accrued interest before placing further orders?
What are the customers performing poorly by not clearing the accrued interest before placing further orders?

The solution required are refined requirement to facilitate modeling, ERD (Conceptual, Logical, and Physical), Database object creation, Sample Data creation, Queries to answer the five questions, and result.

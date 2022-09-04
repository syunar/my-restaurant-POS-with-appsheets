
# My Restaurant Database and Application

Before using data science to help your business the most important thing should be the data right?, So I create the application that collects the transaction and then connects to the database, ER Diagram, Data model design, and Query will use here.

So this project is like Phase 1 to collect the data and then in Phase 2, I will use this data to analyze the customer behavior e.g. customer segmentation and contextual marketing, analyze the products, etc. the point is
 to maintain and increase customers and sales.
## Authors

- [@fronksupakorn](https://github.com/syunar)


## Project's Goals
- to reduce the time for order capturing
- to reduce workload from duplicate workflow
- to collect the transaction data to the database
## Dependencies

- Google Sheet
    - use as the database
    - design data model & ER Diagram
    - query the data from the database to show on the application
- AppSheet
    - connect to database / CRUD (create, read, update, delete)
    - to deploy the application


## Features

On the application we have 5 menus here:
- Invoice
    - select the date you want and then
    - automatically generate invoices in PDF format
- Summary
    - to show the number of orders in each menu
    - so we can use to buy the raw materials and ingredients 
- Orders
    - add/edit/delete the orders
    - invoice button to generate the invoice by individual order
    - check the delivery status
    - check the payment status
- Menu
    - add/edit/delete the menus or products
    - have "open" and "close" status so when you add orders it will show only "open" menu
- Customers
    - add/edit/delete the customers

## Usage/Examples
1. Add some orders
2. Check the total sum orders to buy the raw material
3. Print out the invoices
4. Delivery
5. Payment checking

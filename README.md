# QuickFood
### Description
Simulates an online food ordering system with database integration using the JDBC and SQL. Uses the terminal for user interaction. Demonstrates the following functionality:
* Getting user input on the order details, allowing the user to select previously entered data where relevant
* Maintaining database tables of customers, restaurants and orders
* Option to update previously entered customer information
* Assigning the order to the driver with the smallest load in a given city
* Maintaining a table of drivers and updating the relevant driver's load with each order
* Generating an invoice based on the order details entered by the user, and saving the invoice to a text file
### Installation
The app requires the following to be able to run:
* The JDK
* Microsoft SQL Server
Further the following changes need to be made:
* Set up a server to host the database "QuickFoodMS" (which is included in the repo)
* Add the details in "CaptureOrder.java" required to connect to the QuickFoodMS database


# MobiLink – E-Commerce Application
This is a desktop-based mobile store app built in Java. It lets users sign up, log in, browse mobile phones, add them to a cart, and place orders. The backend uses MySQL, and the UI is made using Java Swing.
<br>
<br>

## Tools & Technologies
* Java Swing – for the GUI
* JDBC – for database connection
* MySQL – for storing data
<br>

## What We Built
We made a basic shopping system for mobile phones where users can:
* Create an account and log in
* View mobile phones with details
* Add/remove items from the cart
* Edit quantities in the cart
* Place an order (which updates the stock in the database)
<br>


## How It Works
1. Login & Registration
* Users can sign up with their name, phone, email, username, and password.
* All inputs are validated (e.g. valid email, phone number must be 11 digits).
* Users can log in using their credentials.

2. Browsing Products
* A list of mobile phones is shown with their brand, price, and stock.
* Each product has an Add to Cart button.

3. Shopping Cart
* Cart shows product name, price, quantity, and total.
* Users can change quantity or remove items.
* A flat shipping fee of Rs. 1000 is added.
* Final order can be placed using the Buy Now button.

<br>

## Code Structure
| Layer Role   | Technology                                 |
|--------------|--------------------------------------------|
| UI Layer     | Forms, Buttons, Tables - Java Swing        |
| Logic Layer  | App logic (cart, auth) - Java Classes      |
| Data Layer   | DB communication - JDBC + MySQL            |
<br>

## Main Java Files
* LoginGui.java – Handles login
* RegisterGui.java – Handles registration
* CartFrame.java – Shows and manages the cart
* MobileManagementPanel.java – Admin panel for products
* DatabaseConnection.java – DB helper class
* Product.java, User.java – Entity classes
<br>

## Key Points
* We used prepared statements to prevent SQL injection.
* The UI is simple and easy to understand.
* The app is structured clearly so it’s easy to update later.
<br>

## Possible Improvements
* Password hashing
* Better product filtering/search
* Payment system
* Order history
<br>

## Conclusion 
This project helped us practice how to make a real-world desktop app in Java using proper layers and database handling. It covers all the basic things you'd expect in a shopping system, and can be expanded further if needed.

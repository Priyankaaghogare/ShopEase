📦 ShopEase – Console Based Shopping & Billing Application

ShopEase is a console-based shopping and billing application built using Core Java & JDBC (Basic Authentication Only).
It allows users to register, login, browse products, manage a shopping cart, and checkout — all through the terminal.
No UI frameworks or web layers are used.


👨‍💻 Author
Priyanka Ghogare
Console-based shopping application in Core Java.

📄 License
This project is for learning and educational purposes.



🚀 Features

👤 User Module

User Registration (Name, Mobile, Email, Username, Password)
User Login with JDBC-based validation
Logout functionality

🛍 Product & Cart Module

Pre-loaded Product Catalog with:

ID

Name

Description

Ratings

Price

Add product to cart (by ID)

Remove product from cart

View selected items

Real-time total price calculation

Checkout & exit


🛠 Tech Stack

| Component      | Technology          |
| -------------- | ------------------- |
| Language       | Core Java           |
| Input Handling | Scanner             |
| Collections    | List, ArrayList     |
| Sorting        | Comparable<Product> |
| Auth Logic     | JDBC                |



📁 Project Structure

src/
 ├─ com.model/
 │   ├─ Product.java
 │   └─ ProductSet.java
 ├─ com.user/
 │   └─ UserRgist.java
 └─ com.service/
     └─ Test.java


 🧩 Key Concepts Used : 

1) Object-Oriented Programming (OOP)
2) Comparable interface for sorting
3) Java Collections API
4) Console I/O using Scanner
5) JDBC for basic authentication


▶ How to Run
Option 1: Through Terminal

Compile:
javac com/service/Test.java

Run:
java com.service.Test

Option 2: Through IDE
Import the project in Eclipse / IntelliJ / NetBeans
Run Test.java class


🖥 Sample Console Flow

---------- Welcome To JavaKart ----------
Register Yourself First...

Enter Name:
Enter Mobile Number:
Enter Email:
Enter Username:
Enter Password:

Registration Successful!

1. Login
2. Logout

[After Login]

Product List:
[Sorted Product Catalog]

1. Add Product
2. Remove Product
3. View Cart
4. Exit

   






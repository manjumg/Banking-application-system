# Banking-application-system 



- **Bank.java** → Interface defining core banking operations
  - **NoBank.java** → Bank implementation with 8.5% interest rate
  - **LotakBank.java** → Bank implementation with 6.5% interest rate
 


🧩 **Class Overview**

1) Bank.java
   Interface that defines standard methods.

2) noBank.java
   A basic bank implementation, maybe with no-interest or limited services.

3) lotakBank.java
   A more feature-rich implementation (like adding interest, etc.).

4) Main.java
   Entry point that allows users to interact with the system and choose between different bank types.

🔹 **Bank.java**
Interface defining standard banking methods:

addMoney(int money)

checkBalance(String password)

withdrawMoney(String password, int money)

getRateOfInterest(int years)

🔸 **NoBank.java**
Implements the Bank interface:

Interest rate: 8.5%

Generates a random account number

Uses a secret code for access control

🔸**LotakBank.java**
Implements the Bank interface:

Interest rate: 6.5%

Uses a password to secure access

Holds balance and account info




📌 **Features**

--> Modular design using interface Bank

--> Multiple bank implementations: noBank, lotakBank

--> Simple console-based interaction (can be extended with GUI or database)

--> Demonstrates polymorphism in Java.


   



📚 **Future Improvements**
--> Add persistence using a database or file system

--> Create a GUI using JavaFX or Swing

--> Enhance error handling and input validation

--> Add support for multiple users

🧑‍💻 **Author**
Your Name – https://github.com/manjumg








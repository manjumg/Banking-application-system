# Banking-application-system 

BankingSystem/
│
├── Main.java                                  # Entry point of the application
├── Bank.java                                  # Bank interface defining standard banking operations
├── noBank.java                                # One implementation of Bank (e.g., No-interest bank)
└── lotakBank.java                             # Another implementation of Bank (e.g., Local bank with interest)

📌 **Features**

--> Modular design using interface Bank

--> Multiple bank implementations: noBank, lotakBank

--> Simple console-based interaction (can be extended with GUI or database)

--> Demonstrates polymorphism in Java.

**Classes Overview**

1) Bank.java
   Interface that defines standard methods like createAccount(), deposit(), withdraw(), etc.

2) noBank.java
   A basic bank implementation, maybe with no-interest or limited services.

3) lotakBank.java
   A more feature-rich implementation (like adding interest, etc.).

4) Main.java
   Entry point that allows users to interact with the system and choose between different bank types.



📚 **Future Improvements**
--> Add persistence using a database or file system

--> Create a GUI using JavaFX or Swing

--> Enhance error handling and input validation

--> Add support for multiple users

🧑‍💻 **Author**
Your Name – https://github.com/manjumg








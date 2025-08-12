# ATM Simulation Java Mini Project — Description
# Project Title:
# Console-Based ATM Simulation

# Overview:
This mini-project is a Java console application that simulates basic ATM operations such as viewing account balance, depositing money, withdrawing money, and viewing a mini-statement of recent transactions. The goal is to demonstrate essential Java fundamentals including classes, interfaces, inheritance, encapsulation, OOP concepts, and collections—ideal for company placement interviews like Cognizant.

# Key Features:
1.User Authentication: Login with ATM card number and PIN.

2.View Balance: Check the current account balance.

3.Withdraw Amount: Withdraw cash (only if sufficient funds; checks for multiples of ₹500).

4.Deposit Amount: Add money to your account balance.

5.Mini Statement: Display a summary of deposit and withdrawal transactions in the session.

6.Exit Option: Securely exit the application.

# Technical Concepts Demonstrated:
1.Interface & Implementation:

AtmOperationInterf (interface) defines ATM actions.

AtmOperationImpl (implemented class) provides logic for each action.

2.Encapsulation:

ATM class maintains private fields (balance, etc.) with public getters/setters.

3.Abstraction:

Users interact through defined methods, not direct data access.

4.Control Flow & Loops:

Menu-driven loop allows multiple transactions per session.

5.Collections:

Stores mini statement using a HashMap.

6.Error Handling:

Validates correct PIN, ATM number, sufficient funds, and withdrawal conditions.

7.Class Structure:
ATM.java: Model class for ATM properties (balance, deposit, withdraw).

AtmOperationInterf.java: Interface for basic ATM operations.

AtmOperationImpl.java: Implements all ATM actions with business logic and transaction recording.

MainClass.java: Contains the main method, user interaction (menu), and drives the application flow.

8.User Experience:
On running the app, the user sees a menu:
Welcome to ATM Machine!!!
1. View Available Balance
2. Withdraw Amount
3. Deposit Amount
4. View Mini Statement
5. Exit

Operations are performed as per user input with real-time feedback and transaction history.

# Banking-Management-system-CPP-

Overview

The code is designed to simulate a basic banking system, allowing users to create accounts, deposit and withdraw money, and display account information.

Classes and Objects

The code defines two classes:

Account: Represents a bank account with attributes such as account number, account holder's name, balance, and account type (current or savings).
Bank: Manages a collection of accounts and provides methods for creating, depositing, withdrawing, and displaying account information.
Member Functions

The Account class has the following member functions:

Account(): Constructor to initialize account attributes.
getAccountNumber(): Returns the account number.
getAccountHolderName(): Returns the account holder's name.
getBalance(): Returns the account balance.
getType(): Returns the account type (current or savings).
deposit(): Deposits a specified amount into the account.
withdraw(): Withdraws a specified amount from the account.
The Bank class has the following member functions:

Bank(): Constructor to initialize the bank's account collection.
createAccount(): Creates a new account and adds it to the collection.
deposit(): Deposits a specified amount into a specified account.
withdraw(): Withdraws a specified amount from a specified account.
displayAccountInfo(): Displays the details of a specified account.
displayAllAccounts(): Displays the details of all accounts in the collection.
Main Function

The main() function is the entry point of the program. It creates a Bank object and provides a menu-driven interface for users to interact with the banking system.

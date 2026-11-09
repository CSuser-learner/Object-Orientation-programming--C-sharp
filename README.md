# Object-Orientation-programming--C-sharp
A C# console-based banking application demonstrating object-oriented programming concepts including encapsulation, inheritance, polymorphism, transaction management, and rollback functionality.

# C# Object-Oriented Banking System

## Project Overview

This project is a console-based banking application developed in C# as part of my Object-Oriented Development studies at Deakin University.

The purpose of this project was to understand and apply Object-Oriented Programming (OOP) concepts by building a simple banking system that manages multiple accounts and performs different types of transactions.

The application demonstrates how classes and objects can be used to organise code, manage account information, and handle banking operations.

## Features

- Create and manage multiple bank accounts
- Deposit money into an account
- Withdraw money from an account
- Transfer money between accounts
- Display account information and balances
- Maintain transaction history
- Reverse supported transactions using rollback
- Handle invalid transactions and prevent repeated execution

## Object-Oriented Programming Concepts

### 1. Encapsulation

Encapsulation is used to protect account information and control how account balances are modified.

The Account class manages account details and provides methods such as Deposit() and Withdraw() to perform operations.

This helps prevent other parts of the program from directly modifying account balances without following the required conditions.

### 2. Inheritance

The banking system uses a common Transaction class as the base for different transaction types.

DepositTransaction, WithdrawTransaction, and TransferTransaction inherit shared functionality from this base class.

This reduces code duplication and makes the program easier to maintain.

### 3. Polymorphism

Polymorphism allows different transaction types to be handled through a common interface or base class.

Each transaction has its own execution logic, while the banking system can process transactions using shared methods.

This makes it easier to introduce new transaction types without changing the overall structure of the application.

### 4. Abstraction

An abstract Transaction class provides a common structure for transactions.

It defines the operations that transaction classes must support while allowing each transaction type to implement its own behaviour.

### 5. Transaction Management and Rollback

The application tracks transaction execution and success.

Rollback functionality is used to reverse supported transactions. For example, a transfer may need to undo a withdrawal if the receiving account cannot accept the deposit.

This demonstrates the importance of maintaining consistent account balances during transaction processing.

## Technologies Used

- C#
- .NET
- Object-Oriented Programming
- Visual Studio Code
- Console Application

## What I Learned

Through this project, I developed a better understanding of how Object-Oriented Programming concepts work together in a practical application.

I learned how to organise code into separate classes, protect data through encapsulation, reuse functionality through inheritance, and handle different transaction types using polymorphism.

I also gained experience with input validation, exception handling, transaction execution, and rollback.

## Relevance to Cybersecurity

As a cybersecurity student, this project helped me understand the importance of controlling access to data and validating operations before changing application state.

Although this is an educational banking simulation rather than a secure production banking system, the programming concepts are relevant to secure software development.

The project provided a foundation for understanding how applications manage sensitive operations and maintain data consistency.


## Academic Context

Developed as part of Object-Oriented Development at Deakin University.

This repository showcases my learning and practical implementation of C# programming and OOP concepts.

# 🏧 ATM System - Java OOP Project

This is a simple Object-Oriented Java application simulating the functionality of an ATM system. It includes support for savings and current accounts, customer management, transactions (withdrawal and transfer), PIN authentication, and PIN updates.

## 📌 Features

- Abstract base class for different types of accounts
- Savings and Current account support
- Customer and debit card modeling
- ATM machine operations:
  - Authentication
  - Withdrawal
  - Transfer
- PIN validation and generation
- Polymorphism through abstract transaction processing

## 🧱 Class Structure

### 1. `AccountATM` (Abstract)
Base class with deposit, withdraw, and balance methods.

### 2. `SavingsAccount` and `CurrentAccount`
Extend `AccountATM` with specific implementations.

### 3. `BankATM`
Represents bank-level information like name and branch.

### 4. `ATM`
Handles user authentication and transactions.

### 5. `Customer`
Contains personal info, linked account, and debit card.

### 6. `DebitCard`
Stores card details and PIN logic.

### 7. `ATMTransaction` (Abstract)
Base for transactions. Subclasses:
- `Withdrawal`
- `Transfer`

### 8. `PinGeneration`
Updates a customer's debit card PIN.

### 9. `ATMSystemMain`
Main class to simulate the system.

## 🚀 Getting Started

### ✅ Prerequisites
- Java JDK 8 or above
- IDE (like IntelliJ IDEA, Eclipse) or CLI for compilation

### ▶️ Run Instructions

1. Clone or download the repository.
2. Open the project in your IDE or navigate to the directory in terminal.
3. Compile and run `ATMSystemMain.java`.

```bash
javac ATMSystemMain.java
java ATMSystemMain

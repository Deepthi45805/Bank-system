# Banking System – Mini Project

A Python-based mini project that simulates basic banking operations through a menu-driven application.

## Project Overview

The Banking System allows users to create an account, securely log in, and perform common banking activities such as checking balance, depositing money, withdrawing money, transferring money, viewing transaction history, and changing their PIN.

## Main Features

* Create a bank account
* Enter name and phone number
* Create a 4-digit PIN
* Generate a unique account number
* Login using Account Number and PIN
* Check account balance
* Deposit money
* Withdraw money
* Transfer money between accounts
* View transaction history
* Change PIN
* Logout

## Python Concepts Used

* Variables & Data Types
* Conditional Statements
* Loops
* Functions
* Lists & Dictionaries
* String Operations
* Modules
* File Handling
* JSON Data Storage

## Modules Used

### `random`

Used to generate unique account numbers.

### `datetime`

Used to record the date and time of transactions.

### `json`

Used to store account information locally.

### `os`

Used to check whether the account data file exists.

## Project Structure

```text
Banking-System-Mini-Project/
│
├── main.py
├── accounts.json
├── README.md
├── .gitignore
└── sample_output.txt
```

## Application Flow

```text
CREATE ACCOUNT
       ↓
Account Number + PIN
       ↓
     LOGIN
       ↓
┌─────────────────────────┐
│      ACCOUNT MENU       │
├─────────────────────────┤
│ 1. Check Balance        │
│ 2. Deposit              │
│ 3. Withdraw             │
│ 4. Transfer             │
│ 5. Transaction History  │
│ 6. Change PIN           │
│ 7. Logout               │
└─────────────────────────┘
       ↓
    LOGOUT
       ↓
   MAIN MENU
```

## How to Run

### Step 1: Install Python

Install Python 3.8 or later.

### Step 2: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 3: Open the Project

```bash
cd Banking-System-Mini-Project
```

### Step 4: Run the Program

```bash
python main.py
```

If your system uses `python3`:

```bash
python3 main.py
```

## Main Menu

```text
======================================
          BANKING SYSTEM
======================================
1. Create Account
2. Login
3. Exit
======================================
```

## Account Menu

After successful login:

```text
======================================
             ACCOUNT MENU
======================================
1. Check Balance
2. Deposit
3. Withdraw
4. Transfer
5. Transaction History
6. Change PIN
7. Logout
======================================
```

## Data Storage

Account information and transaction records are stored locally in:

```text
accounts.json
```

This allows account information to remain available when the program is restarted.

## Project Objective

The main objective is to combine the Python concepts learned so far into one real-world application and understand how individual concepts work together to build a functional system.

## Real-World Connection

This project demonstrates how programming concepts can be used to model a simplified version of real banking applications, including:

* Account management
* Authentication
* Banking transactions
* Transaction records

## Important Note

This is an **educational mini-project** and not a real banking application. The project is designed to demonstrate Python programming concepts and should not be used to store real financial information.

## Author

**Student Mini Project – Banking System**

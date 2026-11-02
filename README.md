# OOP Bank System

A command-line banking application built with **TypeScript** and **Node.js** to practice object-oriented programming. Users enter their account number and then deposit money, withdraw money, or check their balance through an interactive menu.

## Features
- Account lookup by account number, with a welcome message for the matched customer
- **Deposit**, **Withdraw** and **Check Balance** operations
- Insufficient-balance check on withdrawals
- A $1 service fee on deposits over $100
- Interactive menu (arrow keys + Enter) powered by Inquirer.js
- Input validation for unknown account numbers

## OOP concepts demonstrated
- **Interface:** `BankAccount` defines the contract for account operations
- **Classes:** `BankAccount` and `Customer`
- **Encapsulation:** account logic (deposit/withdraw/balance) lives inside the account class
- **Composition:** each `Customer` has a `BankAccount`

## Tech stack
TypeScript · Node.js · Inquirer.js

## Getting started
```bash
git clone https://github.com/umamak064/oop-bank-system.git
cd oop-bank-system
npm install
npx tsc
node index.js
```

## Sample accounts (demo data)
| Account number | Starting balance |
|---|---|
| 1001 | $500 |
| 1002 | $1000 |
| 1003 | $2000 |

## Possible improvements
- PIN-based login
- Transaction history
- Persistent storage (JSON file or database)
- Unit tests

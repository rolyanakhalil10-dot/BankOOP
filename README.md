# 🏦 Bank Management System (C++ OOP)

## 📌 Overview

This project is a **Bank Management System** built using **Object-Oriented Programming (OOP) in C++**. It simulates real-world banking operations such as account management, currency handling, permissions, and a built-in **currency converter**.

The goal of this project is to demonstrate strong understanding of **OOP concepts**, clean architecture, and basic financial logic.

---

## 🎯 Features

### 👤 User & Account Management

* Create bank accounts
* View account details
* Deposit & withdraw money
* Transfer money between accounts

### 💱 Currency System

* Support for multiple currencies (e.g. USD, EUR, IQD, etc.)
* Each account can have a base currency
* Automatic currency conversion during transactions

### 🔁 Currency Converter

* Convert between supported currencies
* Uses predefined exchange rates
* Ensures accuracy during transfers and balance checks

### 🔐 Permissions & Roles

* **Admin**

  * Create / delete accounts
  * Manage users
  * Set currency exchange rates
* **Customer**

  * View balance
  * Deposit / withdraw
  * Transfer money

Permission checks are enforced before performing sensitive operations.

---

## 🧠 OOP Concepts Used

* **Classes & Objects** (Account, User, Bank, Currency, Converter)
* **Encapsulation** (private data with public methods)
* **Inheritance** (Admin & Customer derived from User)
* **Polymorphism** (virtual functions for role-based behavior)
* **Abstraction** (interfaces for currency conversion & permissions)

---

## 🗂️ Project Structure

```
BankProject/
│
├── Account.h / Account.cpp
├── User.h / User.cpp
├── Admin.h / Admin.cpp
├── Customer.h / Customer.cpp
├── Bank.h / Bank.cpp
├── Currency.h / Currency.cpp
├── CurrencyConverter.h / CurrencyConverter.cpp
├── main.cpp
└── README.md
```

---

## ⚙️ How It Works

1. User logs in (Admin or Customer)
2. System checks permissions
3. Requested operation is executed
4. Currency conversion is applied if needed
5. Updated balance is stored and displayed

---

## 🛠️ Technologies Used

* **Language:** C++
* **Paradigm:** Object-Oriented Programming (OOP)
* **Compiler:** g++ / MSVC

---

## ▶️ How to Run

1. Clone or download the project
2. Compile the files:

   ```
   g++ *.cpp -o BankSystem
   ```
3. Run the program:

   ```
   ./BankSystem
   ```

---

## 🚀 Future Improvements

* File handling for data persistence
* Login system with passwords
* Real-time exchange rates
* GUI or Web version

---

## 📚 Educational Purpose

This project is intended for **learning and practicing OOP in C++**, especially for students studying:

* Software Engineering
* Computer Science
* Programming Fundamentals

---

## ✍️ Author

**Your Name Here**

---

⭐ If you find this project helpful, feel free to improve or extend it!

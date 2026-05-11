# 🏦 High-Integrity Bank Management System (C++)

**A robust, modular banking ecosystem engineered in C++ utilizing Object-Oriented Programming (OOP) to handle secure financial transactions and administrative workflows.**

---

## 🚀 Engineering Overview
This system is designed with a focus on data integrity and secure state management. It features a dual-panel architecture (Admin/Customer) and implements custom logic for transaction synchronization and record persistence.

---

## 🔐 Core Technical Features

### **Administrative Control & Audit**
* **Secure Authentication:** Implements username/password verification for full system access.
* **Centralized Management:** Functionality for account creation, deletion, and cross-account transaction monitoring.
* **Audit Logging:** Global transaction history tracking to ensure financial transparency.

### **Customer-Facing Logic**
* **Identity Verification:** Account access secured via unique account numbers and PIN-based validation.
* **Transactional Integrity:** Secure deposit and withdrawal logic with real-time balance updates.
* **Self-Service Actions:** Customers can manage personal records or initiate account closure with PIN-authorized security.

### **Security & Performance Architecture**
* **Cryptographic Logic:** Implementation of PIN and password hashing to prevent plain-text data exposure.
* **Input Masking:** Hidden character input for sensitive credentials in the terminal interface.
* **Throttling Logic:** Automated account locking mechanism (30-second cooldown) after three failed authentication attempts to mitigate brute-force risks.

---

## 🛠️ Technical Stack
* **Language:** C++
* **Standard Template Library (STL):** Utilized for efficient data handling (maps, vectors, stringstreams).
* **Persistence Layer:** Structured CSV-based storage (`data.csv`, `pins.csv`, `user.csv`, `transactions.csv`).
* **Interface:** ANSI-compliant terminal UI for cross-platform (Windows/Linux) compatibility.

---

## 📂 System Logic
1. **Compilation:** `g++ main.cpp -o bank`
2. **Persistence:** On startup, the system parses existing CSV records into memory-efficient data structures.
3. **Operations:** Transactions are validated against hashed PINs before being committed to the permanent log.

---

## 🧑‍💻 Developed By: Team Code Catalyst
* **Anuruddha Kumar Kahar**
* **Purohit Kamleshsingh Savalsingh**
* **Aayush Singh**
* **Shrimali Jainam Ravindrakumar**
* **Joshi Rudram Manojbhai**

---

## ⚠️ Disclaimer
This is a simulation for **educational and architectural research purposes**. While it implements security best practices like hashing and locking, it is not intended for real-world financial deployment.

---
*"Engineering robust solutions today for the challenges of tomorrow."*

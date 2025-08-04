# 🏦 Thebe Bank - Advanced ATM Simulation

![C++](https://img.shields.io/badge/C%2B%2B-17-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows%20%7C%20macOS-lightgrey)

A secure and feature-rich banking system simulation built with C++ that demonstrates modern banking operations with enhanced security features.

## ✨ Features

- **Secure Account Management**
  - Strong password requirements (8+ chars with numbers)
  - Improved XOR encryption with complex key
  - Password change functionality

- **Banking Operations**
  - Deposits and withdrawals with validation
  - Transaction history with timestamps
  - Account balance tracking
  - Daily withdrawal limits (R10,000)

- **Data Persistence**
  - Separate files for user data and transaction logs
  - Proper account updates without data loss

- **Enhanced UI/UX**
  - Clear menu navigation
  - Input validation and error handling
  - Formatted currency display

## 🛠 Technologies Used

- **Core C++17** - Modern C++ features
- **File I/O** - Persistent data storage
- **Standard Template Library** - Vectors and algorithms
- **Time Handling** - Transaction timestamps

## Getting Started

### Prerequisites
- C++17 compatible compiler (g++ 7+, clang 5+, MSVC 2017+)
- Make (optional, for building)

### Compilation & Execution
```bash
# Compile with g++
g++ -std=c++17 -o thebe-bank bank.cpp

# Run the program
./thebe-bank
ecurity Features
Password Encryption: XOR encryption with complex key

Input Validation: All user inputs are validated

Transaction Logging: Complete audit trail of all transactions

Account Protection: Minimum balance requirements

📈 Future Improvements
Graphical user interface (Qt/GTK)

Network support for multi-user access

Interest calculation and savings accounts

Check deposit functionality

Admin interface for account management
- **Input Validation** - Robust user input handling



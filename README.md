# 🏦 Core Banking Management System

A comprehensive C++ console-based banking system featuring client management, secure transactions, and role-based user authentication.

## 📋 Table of Contents
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

### 🔐 Security & Authentication
- **User Authentication System** with login validation
- **Role-based Access Control** with customizable permissions
- **Account Lockout Protection** after failed login attempts
- **Input Validation** for all user inputs

### 👥 Client Management
- **CRUD Operations** for client accounts
- **Account Number Generation** and validation
- **Client Information Management** (personal details, contact info)
- **Account Balance Tracking**

### 💰 Transaction Management
- **Deposit Operations** with confirmation
- **Withdrawal Operations** with balance validation
- **Balance Inquiry** functionality
- **Transaction Security** with user confirmation

### 👤 User Management
- **Multi-user Support** with different permission levels
- **User Registration** and profile management
- **Permission Assignment** (List Clients, Add/Delete/Update, Transactions, etc.)
- **Administrative Controls**

### 🛠️ System Features
- **Modular Screen-based Interface**
- **File-based Data Persistence**
- **Comprehensive Error Handling**
- **Date and Time Operations**
- **Data Validation and Sanitization**

## 🏗️ Architecture

### Object-Oriented Design
- **Inheritance Hierarchy**: Base `clsPerson` class with derived `clsBankClient` and `clsUser` classes
- **Encapsulation**: Private data members with controlled access methods
- **Modularity**: Separate screen classes for different functionalities
- **Separation of Concerns**: Business logic separated from presentation layer

### Design Patterns
- **Screen Pattern**: Each functionality has its dedicated screen class
- **Data Access Layer**: Centralized file operations
- **Input Validation Pattern**: Reusable validation utilities

## 🚀 Installation

### Prerequisites
- C++ Compiler (Visual Studio 2019+ recommended)
- Windows OS (for Visual Studio project files)

### Setup
1. Clone the repository
```bash
git clone https://github.com/yourusername/banking-system.git
cd banking-system
```

2. Open the project
```bash
# Using Visual Studio
BankSystem.sln
```

3. Build and run
- Press `F5` in Visual Studio or
- Build → Build Solution → Debug → Start Without Debugging

## 💻 Usage

### First Run
1. The system starts with a login screen
2. Default admin credentials (if any) or create new user
3. Navigate through the menu options

### Main Menu Options
- **[1] Show Client List**: View all registered clients
- **[2] Add New Client**: Register a new client account
- **[3] Delete Client**: Remove client account
- **[4] Update Client Info**: Modify client details
- **[5] Find Client**: Search for specific client
- **[6] Transactions**: Access transaction menu
- **[7] Manage Users**: User administration (admin only)
- **[8] Logout**: Exit current session

### Transaction Menu
- **Deposit**: Add money to client account
- **Withdraw**: Remove money from client account
- **Total Balances**: View system-wide balance summary

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

⭐ **If you found this project helpful, please give it a star!** ⭐

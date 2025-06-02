# Bank Management System

A comprehensive console-based bank management application built in C++ that provides secure user authentication, client management, and transaction processing capabilities.

## 🌟 Features

### Authentication & Authorization
- **Secure Login System**: Username and password authentication
- **Role-Based Access Control**: Granular permissions system with 7 different access levels
- **User Management**: Admin can create, update, and delete user accounts
- **Protected Admin Account**: Built-in safeguards prevent deletion of admin user

### Client Management
- **Complete CRUD Operations**: Create, Read, Update, Delete client records
- **Duplicate Prevention**: Automatic validation to prevent duplicate account numbers
- **Client Search**: Find clients by account number with detailed information display
- **Data Persistence**: All client data stored in structured text files

### Banking Transactions
- **Deposit Operations**: Secure money deposits with confirmation prompts
- **Withdrawal System**: Balance validation and overdraft prevention
- **Balance Inquiries**: Real-time account balance checking
- **Total Balance Reports**: System-wide balance calculations and reporting

### Data Management
- **File-Based Storage**: Efficient data storage using structured text files
- **Data Integrity**: Built-in validation and error handling
- **Backup & Recovery**: Safe data operations with rollback capabilities

## 🛠️ Technical Implementation

### Architecture
- **Modular Design**: Well-organized functions with single responsibilities
- **Object-Oriented Approach**: Structured data using C++ structs
- **Menu-Driven Interface**: Intuitive navigation system
- **Permission-Based Security**: Bitwise operations for access control

### Key Technologies
- **Language**: C++ (Standard Library)
- **File I/O**: fstream for data persistence
- **Data Structures**: STL vectors for dynamic data management
- **String Processing**: Advanced string manipulation and parsing

### Permission System
The application implements a sophisticated permission system using bitwise operations:

```cpp
enum enMainMenuePermissions {
    eAll = -1,           // Full access
    pListClients = 1,    // View client list
    pAddNewClient = 2,   // Add new clients
    pDeleteClient = 4,   // Delete clients
    pUpdateClients = 8,  // Update client info
    pFindClient = 16,    // Search clients
    pTranactions = 32,   // Access transactions
    pManageUsers = 64    // User management
};
```

## 📋 System Requirements

- **Compiler**: C++11 compatible compiler (GCC, MSVC, Clang)
- **Operating System**: Windows, Linux, or macOS
- **Memory**: Minimal requirements (< 10MB)
- **Storage**: Space for client and user data files

### First Time Setup
1. Run the application
2. Create an admin user with full permissions
3. Log in and start managing clients and users

### Managing Clients
- **Add Client**: Enter account details, PIN, and initial balance
- **Update Client**: Modify existing client information
- **Delete Client**: Remove clients with confirmation
- **Search Client**: Find clients by account number

### Banking Operations
- **Deposits**: Add money to client accounts
- **Withdrawals**: Remove money with balance validation
- **Balance Reports**: View individual or total balances

### User Administration
- **Create Users**: Set up new system users with custom permissions
- **Manage Access**: Configure what each user can access
- **User Maintenance**: Update or remove user accounts

## 🔒 Security Features

- **Input Validation**: Comprehensive data validation and sanitization
- **Access Control**: Permission-based feature access
- **Confirmation Prompts**: Double-confirmation for critical operations
- **Data Protection**: Secure file handling and data integrity checks


## 🎯 Key Accomplishments

- **Robust Architecture**: Designed scalable, maintainable code structure
- **Security Implementation**: Built comprehensive authentication and authorization
- **Data Management**: Implemented efficient file-based data persistence
- **User Experience**: Created intuitive menu-driven interface
- **Performance**: Optimized file operations and memory usage

## 🔧 Technical Highlights

### Advanced C++ Features Used
- **STL Containers**: Vectors for dynamic data management
- **File Streams**: Advanced file I/O operations
- **String Manipulation**: Complex parsing and validation
- **Bitwise Operations**: Efficient permission system
- **Function Overloading**: Flexible parameter handling
- **Reference Parameters**: Efficient data passing

### Code Quality
- **Clean Code**: Readable, well-commented implementation
- **Modular Design**: Separated concerns and single responsibilities
- **Consistent Naming**: Clear, descriptive variable and function names







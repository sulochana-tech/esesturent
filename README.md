# SMAIT Restaurant Management System


A robust, terminal-based restaurant management system built with pure Dart, designed to streamline restaurant operations with a focus on simplicity and efficiency.

---

## 📖 Overview

The SMAIT Restaurant Management System is a command-line interface (CLI) application for managing restaurant operations. It provides a comprehensive solution for small to medium-sized restaurants, covering:

- **Menu Management**: Create, update, and manage menu items with categories and availability.
- **Table Operations**: Book, manage, and track table occupancy and orders.
- **Order Processing**: Handle customer orders with real-time calculations.
- **Inventory Tracking**: Monitor stock levels and manage inventory.
- **Billing & Reporting**: Generate invoices and detailed sales reports.
- **Role-Based Access Control**: Secure access for Admins, Cashiers, and Waiters.

---

## 🛠️ Tech Stack

- **Language**: Dart (Pure, no external dependencies)
- **Storage**: JSON files for data persistence, CSV for sales reports
- **IDE**: Visual Studio Code (recommended)
- **Environment**: Terminal-based CLI

---

## 📂 File Structure

```
restaurant_system/
├── main.dart                    # Application entry point
├── models/                     # Data models
│   ├── user.dart               # User roles and authentication
│   ├── menu_item.dart          # Menu item structure
│   ├── table.dart              # Table management
│   ├── order.dart              # Order details
│   └── inventory_item.dart     # Inventory tracking
├── services/                   # Business logic
│   ├── branch_service.dart     # Branches list  
│   ├── auth_service.dart       # Authentication and role management
│   ├── menu_service.dart       # Menu operations
│   ├── table_service.dart      # Table booking and status
│   ├── order_service.dart      # Order processing
│   ├── billing_service.dart    # Billing and invoice generation
│   ├── inventory_service.dart  # Inventory management
│   ├── tranfer_service.dart    # Resources Tansfer to different branches   
│   └── report_service.dart     # Sales and financial reporting
├── utils/                      # Helper utilities
│   ├── file_handler.dart       # JSON/CSV file operations
│   └── validator.dart          # Input validation
├── data/                       # Data storage
│   ├── users.json              # User credentials
│   ├── menu.json               # Menu items
│   ├── tables.json             # Table statuses
│   ├── inventory.json          # Inventory records
│   └── invoices/               # Generated reports
│       └── sales_report.csv    # Daily sales report
```

---

## 👥 User Roles

| **Role**   | **Permissions**                              |
|------------|----------------------------------------------|
| **Admin**  | Full system control (all operations)         |
| **Cashier**| View orders, process bills, generate reports |
| **Waiter** | Manage tables, take and modify orders        |

---

## 🚀 Features

### 🍽️ Menu Management
- Add, update, or remove menu items.
- Organize items by categories (e.g., Appetizers, Mains, Desserts).
- Toggle item availability based on stock or preference.

### 🪑 Table Operations
- Book and release tables.
- Track real-time table occupancy.
- Associate orders with specific tables.

### 🛒 Order Processing
- Add or remove items from orders.
- Adjust item quantities.
- Automatically calculate order totals with tax and discounts.

### 📦 Inventory Tracking
- Monitor stock levels for ingredients and menu items.
- Update inventory based on order fulfillment.
- Receive low-stock alerts.

### 💸 Billing & Reporting
- Generate detailed invoices for customers.
- Export daily sales reports in TXT and CSV formats.
- Summarize financial performance and inventory status.

---

## 🖼️ System Flow

Below is a simplified flow of the system's operations:

![System Flow Diagram](https://github.com/user-attachments/assets/91d91efe-e2f1-4df6-a545-676280c654b8)

---

## 🛠️ Setup Instructions

### Prerequisites
- **Dart SDK**: Version 3.0 or higher ([Install Dart](https://dart.dev/get-dart))
- **IDE**: Visual Studio Code (recommended) or any Dart-compatible IDE
- **OS**: Windows, macOS, or Linux

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/restaurant-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd restaurant_system
   ```
3. Run the application:
   ```bash
   dart run main.dart
   ```

### Notes
- Ensure you are in the project root directory when running the application.
- The system initializes with sample data in the `data/` folder.

---

## 🧑‍💻 Team Members

| Name               | Role            |
|--------------------|-----------------|
| Sulochana Pokhrel  | Lead Developer  |
| Vihaan Shrestha    | Developer       |
| Yanshu Dangi       | Developer       |


---

## 📜 License

Copyright © 2025 SMAIT Restaurant Management System. All rights reserved.

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## 📬 Contact

For inquiries or support, reach out to the team at:
- **Email**: support@smaitrestaurant.com
- **GitHub Issues**: [Report an Issue](https://github.com/your-repo/restaurant-system/issues)# Restaurant-Management-System

Multiple Restaurant Management System
A comprehensive, web-based system designed to manage multiple restaurants efficiently. This project includes essential features for restaurant management, including table status tracking, reservation management, online ordering integrations, kitchen display, financial reports, and multi-role access controls.

Features
Multi-Restaurant Management: Configure and manage multiple restaurants independently.
User Roles and Permissions: Fine-grained access for roles such as owner, manager, cashier, waiter, and delivery personnel.
Table and Reservation Management: Color-coded table status (occupied, available, dirty, reserved) and detailed reservation tracking with customer information.
Order Management:
In-house Orders: Track orders by table and status.
Takeaway and Delivery: Support for takeaway and online delivery orders with delivery personnel tracking.
Online Ordering Integrations: Seamless integration with platforms such as Yemeksepeti, Trendyol Yemek, and GetirYemek.
Kitchen Display System: Real-time display of orders in the kitchen with order status updates.
Financial and Inventory Reports:
Daily, weekly, monthly, quarterly, and annual reports.
Expense and revenue tracking, including start-of-day and end-of-day reports.
Excel Integration for Product Management: Bulk product import/export through Excel.
Caller ID and Thermal Printer Integration: For caller identification and receipt printing.
Project Structure
index.php: Main landing page with role-based navigation.
fonksiyon/: Folder containing reusable functions and class files.
modules/: Contains various modules such as order management, reservation, table management, and user roles.
api/: API integration files for external ordering platforms.
Installation and Setup
Clone the Repository:

bash
Kodu kopyala
git clone https://github.com/Alyanetwork/multiple-restaurant-management-system.git
cd multiple-restaurant-management-system
Database Setup:

Import the SQL file (located in db/schema.sql) to set up the database structure.
Configure the database credentials in config/database.php.
Dependencies:

Ensure that PHP 7.4 or above is installed.
Install necessary libraries (e.g., for Excel handling and API integrations).
Environment Configuration:

Set up environment variables in a .env file for API keys, database credentials, and other sensitive information.
Run the Application:

Start the server and access the project at http://localhost/multiple-restaurant-management-system.
Usage
Login: Use admin credentials to access all features or test with role-specific credentials for feature-limited access.
Restaurant and Table Management:
Configure multiple restaurants independently.
Manage table statuses in real-time and track reservations.
Order Management:
Track in-house, takeaway, and delivery orders.
Assign and manage delivery personnel and monitor kitchen displays.
Reporting:
Access financial and inventory reports in real-time for individual restaurants.
API Integrations
The system integrates with external platforms for order management and accounting. Configuration for API keys and tokens is required in the .env file.

Yemeksepeti: Real-time order import.
Trendyol Yemek: Order and menu synchronization.
GetirYemek: Automated order updates.
Parasut: Financial synchronization for revenue and expense tracking.
BizimHesap: Detailed expense tracking and accounting integration.
Contributing
Please fork the repository and create pull requests for any new features, bug fixes, or enhancements.

License
This project is licensed under the MIT License.


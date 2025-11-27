Overview
Loveat Pasta is a comprehensive web-based ordering system for a pasta restaurant that allows customers to browse menus, place orders, and track deliveries, while providing staff and admin interfaces for order management and system administration.

Key Features
Customer Features
User Registration & Authentication - Secure account creation and login

Menu Browsing - View pasta dishes with images, descriptions, and prices

Shopping Cart - Add/remove items with quantity controls

Order Placement - Multiple payment options (Cash on Delivery, E-Wallet, Credit Card)

Order Tracking - Real-time status updates with visual progress bar

Order History - View past orders with search and filtering

Account Management - Password changes and account deletion

Staff Features
Order Management - Update order status (Preparing → Ready → On the Way → Delivered)

Dashboard Statistics - View order counts by status

Cancelled Orders - Track and manage cancelled orders

Customer Information - View customer details and order specifics

Admin Features
Menu Management - Add/edit/remove menu items with image upload

User Management - View system users and enable/disable accounts

System Analytics - Track total orders, revenue, and user statistics

Real-time Updates - Live synchronization across all user interfaces

Technical Features
Responsive Design - Works on desktop and mobile devices

Local Storage - Persistent data storage using browser localStorage

Password Security - Simple hashing implementation for password protection

Form Validation - Comprehensive validation for Philippine phone numbers and password strength

Notification System - User-friendly alerts for system events

Auto-complete - Username suggestions for faster login

User Roles & Credentials
Demo Accounts:
Customer: customer / Cus.1

Staff: staff / Staff.1

Admin: admin / Admin.1

Additional Features:
Customer account registration

Password reset functionality

Order cancellation and deletion

Shipping fee calculation based on item count

E-wallet and credit card payment integration with account details

Technology Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)

Styling: Custom CSS with CSS Variables

Icons: Font Awesome 6.4.0

Fonts: Google Fonts (Amatic SC, Poppins)

Storage: Browser localStorage

Images: Local image files

File Structure
text
index.html          # Main application file
image/              # Directory for menu and logo images
  - logo.jpg        # Restaurant logo
  - carbonara.jpg   # Menu item images
  - pesto.jpg
  - ... (other menu images)
Setup Instructions
Clone or download the project files

Ensure all image files are in the image/ directory

Open index.html in a web browser

Use the demo credentials to test different user roles

Browser Compatibility
Chrome (recommended)

Firefox

Edge

Security Notes
Passwords are hashed using a simple algorithm for demonstration

For production use, implement proper backend authentication

Sensitive data is stored in localStorage (consider server-side storage for production)

This system provides a complete restaurant management solution with intuitive interfaces for customers, staff, and administrators, making online pasta ordering seamless and efficient.

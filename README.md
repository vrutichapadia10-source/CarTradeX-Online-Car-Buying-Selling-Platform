# CarTradeX-Online-Car-Buying-Selling-Platform

Developed a Python Flask-based Used Car Buying and Selling Platform that allows users to browse and purchase cars, submit cars for sale, manage wishlists, view profiles, and complete simulated buying/selling transactions. Implemented separate User and Admin functionality with authentication, car listing management, sell-request approval, transaction processing, image upload, filtering, and purchase history. Integrated Flask, PostgreSQL, HTML, CSS, JavaScript, Jinja2 Templates, and psycopg2 for full-stack web application development.

## Key Features
User registration and login
Secure password hashing
User and Admin role-based authentication
Browse available cars
Filter cars by brand, city, price, and kilometers driven
View detailed car information
Buy available cars
Buyer payment/transaction page
Mark purchased cars as SOLD
Store buyer information with purchased cars
Sell car through sell request
Upload car images
Admin dashboard
Admin reviews pending sell requests
Approve or reject car sell requests
Admin-to-seller transaction flow
Buyer-to-admin transaction flow
Transaction records and status management
Wishlist management
User profile
View listed cars
View purchased cars
About page
Session-based authentication
Form validation and error handling
Duplicate transaction prevention
Responsive web interface

## Technologies Used

**Frontend:**
HTML5, CSS3, JavaScript, Bootstrap 5, Jinja2 Templates

**Backend:**
Python, Flask, Flask Routing, Session Management, Werkzeug Security, REST/JSON Responses

**Database:**
PostgreSQL, psycopg2, SQL Queries, Foreign Keys, ENUM Types, Transactions

**Authentication & Security:**
Session-Based Authentication, Password Hashing, Role-Based Access Control, Form Validation

**File Handling:**
Werkzeug secure_filename, UUID-based unique image names, Car Image Upload

**Core Concepts:**
CRUD Operations, SQL Queries, Database Transactions, Dynamic Filtering, Form Handling, HTTP Routes, JSON Responses, Error Handling

## Project Structure
CarTradeX-main/
│
├── app.py
├── db.py
├── test_system.py
│
├── TRANSACTION_IMPLEMENTATION_GUIDE.md
├── TRANSACTION_SYSTEM_IMPLEMENTATION.md
│
├── static/
│   ├── css/
│   │   ├── about.css
│   │   ├── admin.css
│   │   ├── base.css
│   │   ├── buy.css
│   │   ├── car_details.css
│   │   ├── components.css
│   │   ├── home.css
│   │   ├── login.css
│   │   ├── my_profile.css
│   │   ├── sell.css
│   │   ├── signup.css
│   │   ├── transaction.css
│   │   └── wishlist.css
│   │
│   ├── js/
│   │   ├── admin.js
│   │   ├── base.js
│   │   ├── buy.js
│   │   ├── car_details.js
│   │   ├── home.js
│   │   ├── login.js
│   │   ├── my_profile.js
│   │   ├── sell.js
│   │   ├── signup.js
│   │   └── wishlist.js
│   │
│   └── images/
│       └── cars/
│           └── car images
│
├── templates/
│   ├── about.html
│   ├── admin.html
│   ├── admin_transactions.html
│   ├── admin_view_request.html
│   ├── base.html
│   ├── buy.html
│   ├── buyer_payment.html
│   ├── car_cards.html
│   ├── car_details.html
│   ├── home.html
│   ├── login.html
│   ├── my_profile.html
│   ├── sell.html
│   ├── signup.html
│   ├── test.html
│   ├── transaction.html
│   ├── wishlist.html
│   │
│   └── partials/
│       ├── footer.html
│       └── navbar.html
│
└── .vscode/
    └── settings.json

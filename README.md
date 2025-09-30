### Project Overview
This project analyzes an Online Store Orders dataset using PostgreSQL.
The goal is to calculate monthly revenue, order volumes, and top-performing months, while practicing SQL concepts like GROUP BY, SUM(), COUNT(), and date_trunc().

### Repository Structure
├── Orders.csv                  # Dataset (exported from Excel)
├── sales_analysis.sql           # SQL script with CREATE + analysis queries
├── monthly_sales.csv            # Exported monthly revenue results
├── screenshots/                 # Screenshots of queries & charts
│   ├── query_result.png
│   ├── monthly_revenue_chart.png
└── README.md             

### Dataset Description

The dataset (Orders.csv) contains information about customer orders.
Key columns include:
    OrderID → Unique identifier for each order (e.g., ORD200000)
    Date → Order date (DD-MM-YYYY)
    CustomerID → Customer identifier
    Product → Product name (Phone, Laptop, etc.)
    Quantity → Number of items ordered
    UnitPrice → Price per unit
    ShippingAddress → Address of delivery
    PaymentMethod → Debit Card, Credit Card, Online, etc.
    OrderStatus → Shipped, Delivered, Returned, Cancelled, Pending
    TrackingNumber → Tracking code for shipment
    ItemsInCart → Number of items in the customer’s cart
    CouponCode → Discount code (SAVE10, FREESHIP, etc.)
    ReferralSource → Marketing channel (Email, Instagram, Google, etc.)
    TotalPrice → Order value (Quantity × UnitPrice)

 ### Setup Instructions
1 Prerequisites
    PostgreSQL (v13 or higher recommended)
    psql client (command-line tool)
    [Optional] pgAdmin for GUI
2️ Create Schema & Table
3️ Import Dataset
4️ Verify Import

 Analysis Queries
1. Monthly Revenue & Order Volume
2. Top 3 Months by Revenue

Learning Outcomes
Importing CSV into PostgreSQL using \copy
Using GROUP BY, SUM(), COUNT(), and date_trunc()
Handling NULL values with COALESCE()
Finding top results with ORDER BY … LIMIT
Exporting results for visualization
    



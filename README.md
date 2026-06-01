# OMATO Food Delivery Analytics Dashboard

## Project Overview

An interactive Power BI dashboard developed to analyze food delivery operations, customer ordering behavior, payment preferences, restaurant performance, and product demand using sales data from January–April 2023.

The project integrates multiple monthly transaction datasets with dimension tables to create a relational data model for advanced analytics and reporting.

---

## Dataset Structure

### Fact Tables
- January_Sales_2023.xlsx
- February_Sales_2023.xlsx
- March_Sales_2023.xlsx
- April_Sales_2023.xlsx

### Dimension Tables (Omato_Data.xlsx)

#### Food_Details
Contains:
- Food Item ID
- Food Name
- Food Category

#### Customer Details
Contains:
- Customer ID
- Customer Name
- Membership Type

#### Resturant_Details
Contains:
- Restaurant Code
- Restaurant Name
- Restaurant Type

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Excel
- Data Visualization

---

## Dashboard Features

### Executive Dashboard

- Total Quantity KPI
- Total Transactions KPI
- Average Quantity KPI
- Delivery Status Analysis
- Payment Method Analysis
- Monthly Sales Trend
- Top Selling Foods
- Membership Analysis

### Bottom Performance Dashboard

- Bottom Selling Foods
- Monthly Quantity Trends
- Member Type Comparison
- Product Performance Analysis

---

## Key Insights

### Customer Behavior
- Gold members contribute significantly more orders than Regular members.
- Average order quantity is approximately 5–6 items per transaction.

### Product Analysis
- Samosa is the highest-selling food item.
- Paneer Tikka is among the lowest-selling products.

### Payment Analysis
- UPI is the most preferred payment method.
- Card payments have the lowest usage.

### Operations Analysis
- More than 94% of orders are successfully delivered.
- February recorded the highest sales volume.

---

## Data Modeling

The dashboard uses a relational data model connecting:

- Sales Transactions
- Food Details
- Customer Details
- Restaurant Details

This enables cross-filtering and advanced business analysis through Power BI relationships.

---

## Screenshots

### Dashboard Overview

![Overview](Images/dashboard1.png)

### Bottom Analysis

![Bottom Analysis](Images/dashboard2.png)

---

## Repository Structure

OMATO-PowerBI-Dashboard/

├── OMATO_Dashboard.pbix

├── Dataset/

│ ├── January_Sales_2023.xlsx

│ ├── February_Sales_2023.xlsx

│ ├── March_Sales_2023.xlsx

│ ├── April_Sales_2023.xlsx

│ └── Omato_Data.xlsx

├── Images/

│ ├── OMATO_Dashboard.png

│ └── Bottom Analysis_Dashboard.png

└── README.md

---

## Author

Nikhil Pandurang Shinde

B.Tech Electronics and Telecommunication Engineering

Government College of Engineering

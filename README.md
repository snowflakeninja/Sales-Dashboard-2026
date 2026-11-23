# Sales-Dashboard-2026

# Sales Analysis Dashboard | Power BI

## 📌 Project Overview

This project is an interactive Sales Analysis Dashboard created using Microsoft Power BI.

The dashboard provides insights into sales performance, product categories, customer information, and sales trends through interactive visualizations.

This project was developed as part of hands-on Power BI learning, following a guided tutorial by **Data with Baraa**.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data loading and preparation
- **Data Modelling** – Working with related datasets
- **CSV Files** – Data source

## 📂 Dataset Description

The project uses two datasets:

### 1. Orders Dataset
Contains 100 order records with the following columns:

- `order_id` – Unique order identifier
- `order_date` – Date of the order
- `customer_id` – Customer identifier
- `product_name` – Product name
- `product_category` – Product category
- `quantity` – Quantity ordered
- `sales` – Sales amount

### 2. Customers Dataset
Contains 12 customer records with the following columns:

- `customer_id` – Unique customer identifier
- `first_name` – Customer's first name
- `last_name` – Customer's last name
- `country` – Customer's country
- `state` – Customer's state
- `city` – Customer's city
- `score` – Customer score

Both datasets share the `customer_id` field, which can be used to connect customer information with order transactions.

## 📊 Dashboard Features

### 1. Sales by Product
- Bar chart comparing sales across products.
- Helps identify products contributing to overall sales.

### 2. Sales by Product Category
- Donut chart showing the distribution of sales across product categories.
- Helps understand category-wise sales contribution.

### 3. KPI Cards
- Three cards displaying key sales, order, and customer information.
- Provide a quick overview of important business metrics.

### 4. Sales Trend Analysis
- Line chart visualizing sales performance over time.
- Helps understand changes in sales across different periods.

### 5. Interactive Slicers
- Product category slicer
- Country slicer
- Order date slicer

These slicers allow users to filter the dashboard dynamically.

## 🖼️ Dashboard Preview
![Sales Dashboard](screenshots/Sales%20Dashboard.png)

## 🔄 Project Workflow

1. Imported CSV datasets into Power BI.
2. Reviewed data types and available columns.
3. Worked with customer and order data.
4. Created charts to visualize sales performance.
5. Added KPI cards for key metrics.
6. Implemented interactive slicers.
7. Formatted and organized the dashboard.

## 🎯 Skills Practiced

- Data importing and preparation
- Understanding structured datasets
- Data modelling fundamentals
- Data visualization
- KPI card creation
- Interactive dashboard development
- Slicers and filters
- Business data analysis

## 🚀 Future Improvements

- Create DAX measures for total sales, total orders, and unique customers.
- Improve KPI calculations.
- Add more detailed business insights.
- Enhance dashboard formatting and usability.
- Explore advanced Power BI features.

## 📁 Project Structure

```text
powerbi-sales-dashboard/
│
├── sales_project.pbix
│
├── data/
│   ├── customers.csv
│   └── orders.csv
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

## 💻 How to Use

1. Download `sales_project.pbix`.
2. Open it in Microsoft Power BI Desktop.
3. Explore the interactive charts and slicers.
4. If required, update the CSV file paths in Power BI.
5. Refresh the data.

## 🙏 Acknowledgement

This dashboard was developed as a guided learning project following **Data with Baraa's datasets**.

The project helped strengthen my understanding of Power BI, data visualization, and interactive dashboard development.

## 👩‍💻 Author

**Ashmita Mishra**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

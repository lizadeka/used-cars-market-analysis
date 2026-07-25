# 🚗 Used Cars Market Analysis | Power BI Dashboard

## 📌 Project Overview

This project presents an end-to-end business intelligence solution for analyzing the Indian used car market using **Power BI**.

Starting from a raw dataset containing over **140 columns**, the data was cleaned, transformed, and modeled to create an interactive dashboard that provides insights into:

- Vehicle pricing
- Brand performance
- Geographic distribution
- Vehicle specifications
- Market trends
- Customer inventory characteristics

The dashboard is designed to help dealerships, analysts, and decision-makers better understand the used car market through interactive visualizations and business KPIs.

---

# 🎯 Objectives

- Analyze pricing trends across brands and vehicle categories
- Understand regional market distribution
- Identify vehicle usage patterns
- Compare premium and luxury segments
- Build an interactive business dashboard for decision making

---

# 📂 Dataset

**Dataset:** Used Cars Dataset (CarDekho)

The original dataset contained over **140 attributes** related to:

- Vehicle information
- Engine specifications
- Ownership
- Pricing
- Features
- Seller information
- Geographic details

---

# 🧹 Data Cleaning & Transformation

The dataset underwent extensive preprocessing before dashboard development.

### Data Cleaning

- Removed unnecessary columns
- Reduced dataset from **140 columns to 108 columns**
- Removed irrelevant attributes
- Fixed inconsistent values
- Cleaned mileage values
- Cleaned KM Driven values
- Converted price into numeric format
- Standardized vehicle information

---

# ⚙️ Feature Engineering

### Numeric Columns Created

- price_numeric
- km_numeric
- mileage_numeric
- max_power_numeric
- max_torque_numeric

### Derived Columns Created

- car_age
- price_category
- km_category
- luxury_brand

### Power Query Transformations

- Split "Top Features" into separate feature columns
- Cleaned vehicle mileage
- Cleaned KM Driven values
- Prepared numeric fields for analytical calculations

---

# 📊 Dashboard Pages

## 1️⃣ Executive Summary

Provides a high-level overview of the used car market.

### KPIs

- Total Cars
- Average Selling Price
- Average KM Driven
- Average Vehicle Age
- Premium Cars
- Luxury Cars

### Visuals

- Top 10 Brands by Average Selling Price
- Vehicle Distribution by Price Category
- Vehicle Age Distribution
- Vehicle Distribution by KM Category
- Vehicle Listings by Ownership Type

---

## 2️⃣ Geographic & Brand Insights

Explore Regional Markets, Brand Presence & Inventory Distribution.

### KPIs

- Total States
- Total Cities
- Most Listed Brand
- Highest Average Price Brand
- Top Listing City

### Visuals

- Geographic Distribution
- Top Brand Analysis
- Brand-wise Fuel Type Comparison
- State-wise Market Distribution

---

## 3️⃣ Features & Specifications

Explore Vehicle Features, Specifications & Performance Metrics.

Includes analysis of:

- Fuel Type
- Transmission
- Body Type
- Engine
- Mileage
- Vehicle Features
- Performance Specifications

---

# 📈 DAX Measures

The dashboard uses multiple DAX measures for business calculations including:

- Total Listings
- Average Selling Price
- Average KM
- Average Vehicle Age
- Premium Vehicle Count
- Luxury Vehicle Count
- Most Listed Brand
- Most Listed Brand Count
- Highest Average Price Brand
- Highest Average Selling Price
- Top Listing City
- Total States
- Total Cities

Additional DAX measures were created to support dynamic KPIs and dashboard visuals.

---

# 🎨 Dashboard Features

- Interactive Filters
- Dynamic KPIs
- Drill-down Analysis
- Responsive Visualizations
- Business-focused Layout
- Executive Summary Page
- Geographic Insights
- Vehicle Specification Analysis

---

# 💡 Business Insights

- Over **38K** used cars were analyzed.
- The inventory is dominated by budget and mid-range vehicles.
- Maruti has the highest number of listings.
- Rolls-Royce records the highest average selling price.
- First-owner vehicles represent the largest share of listings.
- The inventory is primarily composed of mid-aged vehicles with moderate mileage.

---

# 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

# 📁 Repository Structure

```
📂 Used Cars Market Analysis
│
├── Dashboard.pbix
├── Cleaned Dataset.xlsx
├── Dashboard Screenshots
├── README.md
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Feature Engineering
- Data Modeling
- DAX
- Power Query
- Dashboard Design
- Data Visualization
- Business Intelligence
- Storytelling with Data

---

# 📷 Dashboard Preview

(Add screenshots here)

---

# 📌 Future Improvements

- Predictive price modeling
- Vehicle recommendation dashboard
- Market trend forecasting
- Time-series price analysis
- Interactive drill-through pages

---

# 👨‍💻 Author

Liza Deka

If you found this project useful, consider giving it a ⭐.

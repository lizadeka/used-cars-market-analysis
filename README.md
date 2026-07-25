# 🚗 Used Cars Market Analysis | Power BI Dashboard

## 📌 Project Overview

This project presents an end-to-end Business Intelligence solution developed using the **Used Cars (CarDekho) Kaggle Dataset**. The project was completed collaboratively, with each team member working on a different dataset before combining the analytical findings into a comprehensive Power BI dashboard.

As part of the project, I was responsible for the **Car Details** dataset, where I performed extensive **data cleaning, feature engineering, Power Query transformations, DAX development, and dashboard design**. The raw dataset was reduced from **140 columns to 108 columns**, preparing it for accurate analysis and interactive reporting.

The dashboard provides business insights into:

- Vehicle pricing trends
- Brand performance
- Geographic distribution
- Vehicle specifications and features
- Market and inventory trends
- Vehicle ownership and usage patterns

Designed for dealerships, analysts, and decision-makers, the dashboard transforms raw automotive data into actionable insights through interactive visualizations, business KPIs, and data-driven storytelling.

---

# 🎯 Objectives

- Analyze pricing trends across brands and vehicle categories
- Understand regional market distribution
- Identify vehicle usage patterns
- Compare premium and luxury segments
- Build an interactive business dashboard for decision making

---

# 📂 Dataset

**Dataset:** Used Cars (CarDekho) Dataset – Kaggle

This project was developed using the **Used Cars (CarDekho) Kaggle Dataset**, which consists of two datasets.

### My Dataset

I worked on the **Car Details** dataset, which originally contained **140 columns** covering various aspects of used vehicles, including:

- Vehicle information
- Brand and model details
- Pricing information
- Engine and performance specifications
- Fuel and transmission details
- Ownership history
- Vehicle features
- Geographic information
- Seller details

The dataset was extensively cleaned and transformed before being used for dashboard development.

---

# 🤝 Collaboration & Individual Contribution

This project was completed in collaboration with a teammate using two datasets from the **Used Cars (CarDekho) Kaggle Dataset**.

To ensure efficient development, the work was divided as follows:

### My Contribution

I worked on the **Car Details** dataset and was responsible for:

- Cleaning and transforming the dataset using **Power Query**
- Reducing the dataset from **140 columns to 108 columns** by removing unnecessary attributes
- Correcting unrealistic odometer (KM Driven) anomalies
- Creating numeric columns for analytical calculations
- Engineering derived columns (`car_age`, `price_category`, `km_category`, and `luxury_brand`)
- Normalizing the **top_features** column and creating a separate **Vehicle Features** table
- Developing DAX measures and KPIs
- Designing and building the complete Power BI dashboard

### Teammate's Contribution

My teammate worked on the **Car Data** dataset and was responsible for its data preparation and analysis.

Both datasets together contributed to the overall project and dashboard development.

---

# ⚙️ Data Preparation & Feature Engineering

A significant portion of this project focused on preparing the **Car Details** dataset for analysis. Using **Power Query**, the raw data was cleaned, transformed, and enhanced through feature engineering to improve data quality, ensure analytical accuracy, and support the development of reliable KPIs, DAX measures, and interactive Power BI dashboards.

## Data Cleaning

- Reduced the dataset from **140 columns to 108 columns** by removing unnecessary and low-value attributes.
- Cleaned inconsistent and missing values across multiple columns.
- Corrected **unrealistic odometer (KM Driven) anomalies**, improving the accuracy of vehicle usage analysis, KPIs, and dashboard insights.
- Standardized vehicle specifications for consistent reporting.
- Converted text-based numeric fields into analytical numeric columns.

## Numeric Columns Created

The following numeric columns were created to enable calculations and visualizations:

- `price_numeric`
- `km_numeric`
- `mileage_numeric`
- `max_power_numeric`
- `max_torque_numeric`

> **Note:** During data import, the original **price** column remained as text. After changing its data type in Power BI, a numeric column named **`pu`** was created. All DAX measures, KPIs, and price-related visuals were built using the **`pu`** column instead of the original text field.

## Derived Columns Created

Additional business-focused columns were engineered to improve analysis:

- `car_age`
- `price_category`
- `km_category`
- `luxury_brand`

These derived columns enabled market segmentation, inventory classification, and interactive filtering throughout the dashboard.

## Vehicle Features Transformation

The original **top_features** column stored multiple features as comma-separated text.

Using **Power Query**:

- Split the comma-separated values into individual rows.
- Normalized the feature data.
- Created a separate **Vehicle Features** table.
- Enabled analysis of the **Top 10 Most Common Vehicle Features** across the inventory.

This transformation allowed feature-level analysis that was not possible using the original dataset structure.

---

# 📊 Dashboard Pages

## 📄 Page 1: Executive Summary

The Executive Summary provides a high-level overview of the used car market by combining key business KPIs with interactive visualizations. It enables users to quickly understand the overall market size, pricing landscape, inventory quality, and ownership patterns before exploring detailed analyses.

### 📌 Business Insights

#### Key Performance Indicators (KPIs)

- **38K+** used cars were analyzed, providing a comprehensive view of the market.
- The **average selling price is ₹8.59 lakh**, indicating a market primarily focused on affordable and mid-range vehicles.
- Vehicles have an **average mileage of 65K km**, reflecting moderate usage across the inventory.
- The **average vehicle age is 10 years**, highlighting a mature used car market.
- Around **3K premium vehicles** are available, while only **38 luxury vehicles** exist, showing that the luxury segment represents a very small share of the inventory.

#### Dashboard Insights

- **Rolls-Royce** records the **highest average selling price** among all brands, significantly outperforming other manufacturers.
- **3-year-old vehicles** have the **highest average selling price**, indicating strong resale value in newer vehicles.
- The inventory is largely concentrated in the **Budget** price segment, showing that the marketplace mainly serves value-conscious buyers.
- **First-owner vehicles** dominate the inventory, suggesting better resale quality and stronger buyer confidence.
- Most vehicles fall within the **Medium and High KM categories**, indicating that the majority of listed vehicles have been actively used rather than being low-mileage cars.

---



---

## 📄 Page 4: Features & Specifications

This page explores the technical specifications and feature availability of vehicles in the inventory. It helps users understand vehicle performance, fuel efficiency, transmission preferences, and the most common features offered across different vehicle segments.

### 📌 Business Insights

#### Key Performance Indicators (KPIs)

- Vehicles offer an **average engine power of 106.70 bhp**, making the inventory suitable for both city and highway driving.
- The **average torque is 191.16 Nm**, indicating balanced vehicle performance across different models.
- Most vehicles have an **average seating capacity of 5**, reflecting the popularity of family-oriented passenger cars.
- The **average fuel efficiency is 19.42 km/l**, highlighting a good balance between performance and fuel economy.
- **Luxury vehicles account for only 10.8% of the inventory**, showing that the marketplace is largely dominated by non-luxury vehicles.

#### Dashboard Insights

- **Hatchbacks and Sedans** represent the largest share of vehicle body types, making them the most common choices in the used car market.
- **Air Conditioner, Power Steering, Heater, Power Windows (Front), and Adjustable Headlights** are the most frequently available vehicle features, indicating that these have become standard offerings.
- **Electric vehicles record the highest average fuel efficiency (88.62 km/l equivalent)**, followed by **CNG vehicles (27.45 km/l)**, demonstrating the efficiency advantage of alternative fuel vehicles.
- **Petrol vehicles dominate the inventory**, while **Diesel vehicles** form the second-largest segment of the market.
- **Manual transmission vehicles account for nearly three-fourths of the listings (73.74%)**, indicating a significantly higher market presence compared to automatic vehicles.

---

## 📄 Page 5: Geographic & Brand Insights

This page analyzes the geographic distribution of vehicle listings and brand performance across different regions. It provides insights into regional market concentration, leading automotive brands, fuel preferences, and city-wise inventory distribution.

### 📌 Business Insights

#### Key Performance Indicators (KPIs)

- The inventory covers **31 states and 489 cities**, indicating a wide geographic presence across India.
- **Maruti** is the **most listed brand** with over **10K vehicle listings**, reflecting its strong dominance in the used car market.
- **Rolls-Royce** records the **highest average selling price (₹9.55 crore)**, making it the most premium brand in the inventory.
- **New Delhi** has the highest number of vehicle listings, making it the largest regional market in the dataset.

#### Dashboard Insights

- **Maharashtra, Uttar Pradesh, Gujarat, Haryana, Rajasthan, Telangana, and Tamil Nadu** account for the largest share of vehicle listings, highlighting major regional markets for used cars.
- **Maruti, Hyundai, and Honda** dominate the market, with Maruti holding the largest overall market share.
- **Petrol vehicles dominate the inventory for leading brands**, while diesel remains the second most preferred fuel type across major manufacturers.
- **Rolls-Royce and Ferrari** lead the market in terms of average selling price, representing the ultra-premium segment.
- **New Delhi (5.9K listings) and Pune (4.6K listings)** emerge as the leading cities in the dataset, indicating strong used-car market activity in these major urban centers.

---

# 📈 DAX Measures

The dashboard uses multiple DAX measures for business calculations including:

### Core Business Measures

- Total Cars
- Total Listings
- Total States
- Total Cities
- Total Premium Cars
- Average Selling Price
- Average Vehicle Age
- Average Engine Power
- Average Torque
- Average Fuel Efficiency
- Luxury Vehicle Share
- Average Sitting Capacity
- Top Listing City

### Brand Performance Measures

- Most Listed Brand
- Most Listed Brand Count
- Most Listed Brand Name
- Highest Average Price
- Highest Average Price Brand
- Highest Average Price Brand Name
  
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

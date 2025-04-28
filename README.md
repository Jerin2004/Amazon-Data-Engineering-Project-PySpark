# 🔍 Amazon Data Engineering Project on Databricks 🚀

## Overview
This project analyzes Amazon product data using PySpark on Databricks to derive insights about pricing, discounts, and customer reviews across various product categories.

## Features
- **Data Processing**: Clean and transform raw product data
- **Analytics**:
  - Price optimization analysis
  - Discount effectiveness
  - Review sentiment trends
- **Visualization**: Generate actionable business insights

## Dataset
The dataset contains:
- 50,000+ product listings
- Pricing history with discounts
- Customer ratings and reviews
- Product metadata

Sample data structure:

| Column               | Type      | Description                     |
|----------------------|-----------|---------------------------------|
| product_id           | String    | Unique product identifier       |
| discounted_price     | Decimal   | Current selling price           |
| actual_price         | Decimal   | Original price                  |
| discount_percentage  | Decimal   | Calculated discount percentage  |
| rating               | Float     | Customer rating (1-5)           |

## Getting Started

### Prerequisites
- Databricks workspace
- PySpark 3.0+ cluster
- Dataset uploaded to DBFS

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amazon-data-engineering.git
